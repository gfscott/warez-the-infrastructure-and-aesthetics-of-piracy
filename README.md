# _Warez: The Infrastructure and Aesthetics of Piracy_, by Martin Paul Eve
## ePub version

This repo contains the raw materials for my conversion of [_Warez_](https://punctumbooks.com/titles/warez-the-infrastructure-and-aesthetics-of-piracy/), published by [punctum books](https://punctumbooks.com/), into ePub format.

_Warez_, like nearly all of punctum’s books, was originally released as a free PDF, but I found that difficult to read on my phone. Since it was released under a CC BY-NC-SA 4.0 International licence, I took the liberty of format-shifting the text and re-releasing it here. [This comment](https://punctumbooks.com/titles/warez-the-infrastructure-and-aesthetics-of-piracy/#comment-215720) from punctum books co-director Eileen Joy suggests they’re cool with that.

Special thanks of course to Martin Paul Eve and punctum books for releasing the book under a permissive licence that allows this knowledge to be shared.

## Build process

I use pandoc to generate the book from the markdown files. I grabbed the text from the original PDF and edited it by hand.

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
  bibliography.md \
  --reference-location=section \
  --file-scope
```

The `--reference-location` and `--file-scope` flags are necessary to properly parse the footnotes in each chapter file. If you run the conversion without them, then you get a pandoc error where the footnote numbers conflict, because they re-start at 1 with each chapter.

## Relevant links

- [Creating an ebook with pandoc](https://pandoc.org/epub.html)
- [pandoc manual for epubs](https://pandoc.org/MANUAL.html#epubs)
