# Food Picture — Lacquered Roast Duck

Entry for make.fun bounty **food-picture-01** ("Make the best-looking
food picture", $250, top 100 share the prize).

## What it is

`main.py` (Python 3.13, standard library only) copies `art.jpg` to
`$MAKEFUN_OUTPUT_DIR/entry.png`, after checking the JPEG magic bytes,
the end marker, and the 1 MiB size limit. That is the whole program:
one picture of food, written deterministically, no network.

## The picture

A whole lacquered roast duck with deep mahogany, glistening crispy
skin, on a dark charcoal slate board — orange wedges, red chilies and
fresh herbs around it, wisps of steam rising, dark moody background
with warm side light. One clear hero dish, rich saturated colour, and
a shape that still reads at small size.

`art.jpg` is a JPEG (1024x1024, 223,416 bytes, quality 90) made from
the 1600x1600 render of the same image; only the size and encoding
changed, not the composition.

## Running it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.png
```
