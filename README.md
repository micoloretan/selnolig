selnolig
========

All files associated with the LuaLaTeX package "selnolig". 

The selnolig package lets users suppress typographic ligatures based on predefined search patterns. 
The search patterns focus on ligatures deemed inappropriate because they span morpheme boundaries. 
For example, the word shelfful, which is mentioned in the TeXbook as a word for which the "ff" ligature 
might be inappropriate, is automatically typeset as shelf\/ful rather than as shel\mbox{ff}ul.

For English and German language documents, the selnolig package provides ligature suppression macros  
for the so-called "common" f-ligatures. These comprise not only the familiar ff, fi, fl, ffi, and ffl 
ligatures but also the ft and fft ligatures.

For English language documents, the package also provides ligature suppression macros for a number of 
so-called discretionary/rare and historic ligatures.

The selnolig package requires the LuaLaTeX format provided by a reasonably modern TeX distribution such 
as TeXLive2012, MacTeX2012, or MiKTeX2.9.

To get started, you should (i) download the package's .sty (style) files and the file selnolig.lua and 
(ii) install these files in a directory in a way that's appropriate for your TeX distribution. The user 
guide is in the file selnolig.pdf.

The files README.md (the file you're currently reading), .gitignore, and .DS_Store are *not* part of the 
package and need not be downloaded. The files with extension .tex and .fea need only be downloaded if
you're interested in compiling the source code yourself.
