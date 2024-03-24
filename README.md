# _Warez: The Infrastructure and Aesthetics of Piracy_, by Martin Paul Eve

## EPUB version 

✨ [**Download the latest version via the Releases tab**](https://github.com/gfscott/warez-the-infrastructure-and-aesthetics-of-piracy/releases)

This repo contains the text files for my EPUB conversion of [_Warez: The Infrastructure and Aesthetics of Piracy_](https://punctumbooks.com/titles/warez-the-infrastructure-and-aesthetics-of-piracy/), originally published by [punctum books](https://punctumbooks.com/) and re-released here, somewhat ironically, with the permission of the author.

_Warez_, like nearly all of punctum’s books, was originally released as a free PDF, but I found that format difficult to read on my phone. Since it was released under a [CC BY-NC-SA 4.0 International](LICENSE) licence, I took the liberty of format-shifting the text. punctum books co-director Eileen Joy has previously indicated that [they’re cool with that](https://punctumbooks.com/titles/warez-the-infrastructure-and-aesthetics-of-piracy/#comment-215720).

Special thanks of course to Martin Paul Eve and punctum for releasing the book under a permissive licence that allows this knowledge to be shared. I’ve made a donation to punctum to support their work, and if you download the EPUB version I [encourage you to do the same](https://punctumbooks.com/support/).

## Build process

I use [pandoc](https://pandoc.org) to generate the ebook from the markdown files. I grabbed the text from the original PDF and, for the most part, edited it by hand.

```sh
pandoc -o warez.epub \
  00-preface.md \
  01-original-pirate-material.md \
  02-setting-the-scene.md \
  03-infrastructures-of-the-scene.md \
  04-organization.md \
  05-aesthetics.md \
  06-takedowns.md \
  07-conclusion.md \
  appendix.md \
  bibliography.md \
  --reference-location=section \
  --file-scope
```

The `--reference-location` and `--file-scope` flags are necessary to properly parse the footnotes in each chapter file. If you run the conversion without them, then you get a pandoc error where the footnote numbers conflict, because they re-start at 1 with each chapter.

## Relevant links

- Buy the book: [_Warez: The Infrastructure and Aesthetics of Piracy_](https://punctumbooks.com/titles/warez-the-infrastructure-and-aesthetics-of-piracy/)
- Author: [Martin Paul Eve](https://eve.gd)
- Publisher: [punctum books](https://punctumbooks.com/)
- [Creating an ebook with pandoc](https://pandoc.org/epub.html)
- [pandoc manual for epubs](https://pandoc.org/MANUAL.html#epubs)
