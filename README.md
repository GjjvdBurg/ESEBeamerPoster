ESEBeamer
=========

Unofficial Beamer Poster style for the Erasmus School of Economics.

Author: Gertjan van den Burg

This code is released under the GPL License (v2) (see LICENSE).

Usage
-----
See the file `example.tex`. Include the following command
in the preamble of the tex file:

    \usetheme{RotterdamPoster}

Options are:

  - emphasizegreen: highlight using the EUR green colour
    instead of black
  - structgreen: use EUR green as the structure colour 
    (this changes the colour of bullets etc.)
  - logogreen: use the EUR green logo instead of the black
    one.

Installation
------------

- Linux: See http://tex.stackexchange.com/a/1138. Create a
         local directory ~/texmf/tex/latex/beamer/rotterdam_poster
         and place the beamerthemeRotterdamPoster.sty file in 
         this folder, together with the required pdf 
         images. Finally, update the package database with 
         texhash or mktexlsr. Summarizing:

             mkdir -p ~/texmf/tex/latex/beamer
             git clone https://github.com/GjjvdBurg/ESEBeamerPoster.git ~/texmf/tex/latex/beamer/rotterdam_poster
             sudo texhash

- Windows: See http://tex.stackexchange.com/a/2066. Note: it is 
           also possible to use the style by placing all necessary
           files (.sty, .pdf) in the same folder as your current
           project.
