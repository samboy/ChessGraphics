# About this project

This is a project to make public domain fonts for Chess games.  While
a number of Chess piece diagram fonts are available, none of them, to the
extent of my knowledge, are public domain.

In keeping with Armando Hernandez Marroquin’s naming scheme for
Chess Merida, these fonts are named after beautiful places in Mexico 
I have been to.

# Cuernavaca

Chess Cueravaca is a public domain font suitable for making Chess
diagrams.  Its graphics are mostly based on public domain vector files
available at the Wikimedia commons.  Those vector files are in turn 
based on raster PNG images.  The PNG images, in turn, are renderings
of symbols in the open source 
[Skak Chess Font](https://github.com/lehoff/skak), but do not, as per 
*Eltra Corp. v. Ringer*, fall under the license for that font.  
Since the SVG files are derived from raster PNG images, 
*Adobe Systems, Inc. v. Southern Software, Inc.* does not apply.

Note that this font is *not* public domain in jurisdictions which
allow fonts to be copyrighted, but is still available under an
[open source license](https://github.com/lehoff/skak/blob/master/LICENSE).
Since some jurisdictions which protect fonts only protect them for
shorter terms, it appears that the Shak font was first published in
2002, so copyright expired before 2013 in Germany (10 years protection
without registration), and expired before 2018 in Ireland (15 years
protection).

To use, install the `ChessCuernavaca.ttf` file in the `Cuernavaca/`
folder.

The .svg files used in making the font are available in the 
`Cuernavaca/SVG` directory.

Here is a diagram made with the font:

![Cuernavaca Chess Font](https://raw.githubusercontent.com/samboy/ChessGraphics/main/CuernavacaDemoSmall.png)

There is some support for fairy chess pieces.

# Tepoztlan

Chess Tepoztlan is a public domain font suitable for making Chess
diagrams.  The font is a vector conversion of the images in SmallPng.

The images are very loosely derived from two 19th century works:

* Images on the front cover of Benjamin R. Foster’s 1889 book 
  *Chancellor Chess*.
* An image of a knight in Theophilus Thompson’s 1873 classic 
  *Chess Problems: Either to Play and Mate*.

To use, install the `ChessTepoztlan.ttf` file in the `Tepoztlan/` 
folder.

The .svg files used in making the font are also available in this
directory.

Here is a diagram made with the font:

![Tepoztlan Chess Font](https://raw.githubusercontent.com/samboy/ChessGraphics/main/TepoztlanDemoSmall.png)

There is some support for fairy chess pieces.

In addition, I have made small png images for the black pieces.

# Jiutepec

Chess Jiutepec is a font which uses versions of the Chess symbols in the 
[Quivira font](http://quivira-font.com/).  Like the other fonts, the
font is public domain.

The interface for making diagrams with the font is identical with the
other fonts.

![Jiutepec Chess Font](https://raw.githubusercontent.com/samboy/ChessGraphics/main/Jiutepec/ChessJiutepecDemoSmall.png)

# Using the fonts

All fonts here have the same mapping:

* `A` is a white upsidedown bishop
* `S` is a black upsidedown bishop
* `D` is a white rook + knight fairy piece (or upsidedown rook)
* `F` is a black rook + knight fairy piece (or upsidedown rook)
* `G` is a white upsidedown knight
* `H` is a black upsidedown knight
* `P` is a white pawn
* `O` (the letter) is a black pawn
* `R` is a white rook
* `T` is a black rook
* `N` is a white knight
* `M` is a black knight
* `B` is a white bishop
* `V` is a black bishop
* `Q` is a white queen
* `W` is a black queen
* `K` is a white king
* `L` is a black king
* A `+` is an empty black square
* A ` ` (blank space) is an empty white square
* To put a border around a chess diagram, use `!"#` on the top row,
  `$` on the left side, `%` on the right side, and `/()` on the 
  bottom.
* Examples of the fonts being used in documents are in the folders
  `Tepoztlan/Examples` and `Wikimedia/Examples`.

Uppercase pieces are on black squares; lowercase pieces are on white
squares.

Note that the mapping is (generally) compatible with Chess Merida
and Armando Hernandez Marroquin’s other excellent freeware
Chess fonts.

The following text looks like the starting position for Modern Carrera
Chess (where an upsidedown bishop also has the knight’s move, and the
piece which is a knight with rook is the rook + knight piece) in the 
ChessTepoztlan font:

```
!""""""""""#
$tSmVwLvMfT%
$OoOoOoOoOo%
$ + + + + +%
$+ + + + + %
$ + + + + +%
$+ + + + + %
$pPpPpPpPpP%
$RaNbQkBnDr%
/(((((((((()
```

Note that the font works best on a QWERTY keyboard (since the corresponding
black piece is next to the white piece; e.g. `V` is a black bishop where
`B` is a white bishop).  Uppercase is a dark square; lower case is a
light square.

# SmallPng

The SmallPng directory consists of low resolution Png files.

The .png files mainly come from my first-2000s-decade attempt to make
public domain graphics for the Chess Variant playing engine Zillions of
Games.  Since this engine only supported low-resolution bitmap graphics,
the images here are low resolution png files.

The images are based on 19th century Chess images, which, due to their
age, are public domain.

Since I was unable to find a suitable public domain Knight image back
then, I recently took an image of a Knight from Theophilus Thompson’s
1873 classic *Chess Problems: Either to Play and Mate*.  The other
images are very loosely based on images on the front cover of
Benjamin R. Foster’s 1889 book *Chancellor Chess*.

In both cases, the images are Public Domain: They were published before
1922 (yes, here in 2022, the cut off is before 1927, but it was 1922 when 
I made most of these images).
