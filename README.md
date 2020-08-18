# mangadex-epub-dl
*working title*

Creates properly tagged EPUB files downloaded from Mangadex. These EPUB files can then be passed to KindleGen or imported into Calibre for viewing on a Kindle e-reader.

## Roadmap

- Given the output of [mangadex-downloader](https://github.com/bibo5088/mangadex-downloader) and the manga ID used, create a tagged EPUB file.
	- Investigate the HTML that Calibre's plugins output for its CBC → EPUB plugin.
	If the license is bad (it's probably GPL though) then *only look at the output of the plugin*.
- Write the actual downloader in python, probably using [aiomangadex](https://pypi.org/project/aiomangadex/). This also allows us to download the images and metadata in one step.
