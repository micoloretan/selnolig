selnolig
========

All files associated with the LuaLaTeX package "selnolig". 

The selnolig package suppresses typographic ligatures selectively, i.e., based on predefined search patterns. The search patterns focus on ligatures deemed inappropriate because they span morpheme boundaries. For example, the word \opt{shelfful}, which is mentioned in the TeXbook as a word for which the ff ligature might be inappropriate, is automatically typeset as shelf\/ful rather than as shel{ff}ul.

For English and German language documents, the selnolig package provides extensive rules for the selective suppression of so-called "common" ligatures. These comprise the ff, fi, fl, ffi, and~ffl ligatures as well as the ft and~fft ligatures. Other f-ligatures, such as fb, fh, fj and fk, are suppressed globally, while making exceptions for names and words of non-English/German origin, such as Kafka and fjord.

For English language documents, the package further provides ligature suppression macros for a number of so-called "discretionary" or "rare" ligatures such as ct, st, and sp.

<<<<<<< HEAD
The selnolig package requires use of the LuaLaTeX format provided by a recent TeX distribution such as TeXLive2012 or~2013 and MiKTeX2.9.
=======
The selnolig package requires use of the LuaLaTeX format provided by a recent TeX distribution such as TeXLive2012 or~2013 and MiK2.9.
>>>>>>> 45dfb1ef888db81a7f021b0ff78c34abbc1e391b

To get started, you should (i) download the package's .sty (style) files and the file selnolig.lua and 
(ii) install these files in a directory in a way that's appropriate for your TeX distribution. The package's user 
guide is in the file selnolig.pdf.

The files README.md (the file you're currently reading), .gitignore, and .DS_Store are *not* part of the 
package and need not be downloaded. The files with extension .tex and .fea need only be downloaded if
you're interested in compiling the source code yourself.
