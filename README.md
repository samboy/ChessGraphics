# About this project

This is a project to make public domain graphics for Chess games.  While
a number of Chess piece graphics are available, none of them, to the
extent of my knowledge, are public domain.

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
Benjamin R. Foster’s 1887 book *Chancellor Chess*.

In both cases, the images are Public Domain: They were published before
1922 (yes, here in 2022, the cut off is before 1927, but it was 1922 when 
I made most of these images).

# Tepoztlan

Chess Tepoztlan is a public domain font suitable for making Chess
diagrams.  The font is a vector conversion of the images in SmallPng.
In addition, I made additional small png images for the black pieces.

The .svg files used in making the font are also available in this
directory.

Here is a diagram made with the font:

![Tepoztlan Chess Font](https://raw.githubusercontent.com/samboy/ChessGraphics/main/TepoztlanDemoSmall.png)

# The chess pieces

* A is a white upsidedown bishop
* S is a black upsidedown bishop
* D is a white rook + knight fairy piece
* F is a black rook + knight fairy piece
* G is a white upsidedown knight
* H is a black upsidedown knight
* P is a white pawn
* O (the letter) is a black pawn
* RNBQK are the expected white pieces (as per English algebraic notation)
* TMVWL are the corresponding black pieces
* A `+` is an empty black square
* A ` ` (blank space) is an empty white square

Note that the mapping is (generally) compatible with Chess Merida
and Armando Hernandez Marroquin’s other excellent freeware
Chess fonts.

Uppercase pieces are on black squares; lowercase pieces are on white
squares.

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

