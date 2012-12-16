selnolig
========

The LuaLaTeX package "selnolig" serves to suppress typographic ligatures automatically based on predefined search patterns for English and German language documents. The search patterns focus on ligatures deemed inappropriate because they span morpheme boundaries within words. For example, the word shelfful, which is mentioned in the TeXbook as a word for which the ff-ligature might be inappropriate, is automatically typeset as shelf[]ful rather than as shel[ff]ul.

The selnolig package provides ligature suppression macros for the common typographic f-ligatures for both English and German language documents. These comprise not only the familiar ff, fi, fl, ffi, and ffl ligatures, but also ligatures such as ft and fft, which are frequently provided by many fonts suitable for typesetting text.

For English language documents, the package also provides ligature suppression macros for a selection of discretionary and historic ligatures.

*** The main macros of the selnolig package require the use of the LuaLaTeX format. A reasonably modern TeX distribution -- such as TeXLive2012, MacTeX2012, or MiKTeX2.9 -- is also required. ***

The package's user guide may be found in the file selnolig.pdf.

To start using this package, you should at a minimum download the *.sty files and the selnolig.lua file to a suitable directory in your personal TeX directory or the localtexmf directory. (The precise location will depend on your TeX distribution.)

Please note that the files README.md, .gitignore, and .DS_store are not part of the selnolig package. Thus, they need not be downloaded in order to utilize the selnolig package.
