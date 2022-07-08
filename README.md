# Gridfinity Containers

Here you'll find a large collection of renders of #gridfinity containers from @vector76'es https://github.com/vector76/gridfinity_openscad, which has a couple modifications from the original by Zach Freedman:

* Magnet holes are sized such that a 6mm magnet can be press-fit without needing glue
* Magnet holes have a bit of a internal cone which should reduce sagging of filament into the magnet hole when the hole is bridged
* Space for label is optional
* Space for finger slide is optional

## Decoding filenames

Renders are divided into folders for easy browsing, but the resulting filenames have some extra bits of information as well.  The filenames have the format `basic_cup_L#_W#_H#_C#_M#_L#_F#.stl`, where each `#` corresponds as follows:

| Key | Description |
|-----|-------------|
|  L  | Size of the container in the Y dimension, in gridfinity cube units |
|  W  | Size of the container in the X dimension, in gridfinity cube units |
|  H  | Size of the container in the Z dimension, in gridfinity 7mm height units.  H6 is a standard full-height container |
|  C  | Number of chambers in the container |
|  M  | Depth of the magnet holes. M0 means no magnet holes, M2 means it accepts 6mm by 2mm magnets |
|  L  | Space for label?  y or n |
|  F  | Finger slide on the bottom?  y or n |
