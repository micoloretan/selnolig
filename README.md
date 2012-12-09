selnolig
========

The selnolig package suppresses typographic ligatures automatically based on predefined search patterns for English and German language documents. The search patterns focus on ligatures deemed inappropriate because they span morpheme boundaries within words. For example, the word shelfful, which is mentioned in the TeX book as a word for which the ff-ligature might be inappropriate, is automatically typeset as shelf[]ful rather than as shel[ff]ul.

The selnolig package provides ligature suppression macros  for the common typographic f-ligatures. These comprise not only the familiar ff, fi, fl, ffi, and ffl ligatures, but also ligatures such as ft and fft, which are frequently provided by many fonts suitable for typesetting text.

For English language documents, the package also provides ligature suppression macros for a selection of discretionary and historic ligatures.

*** The selnolig package requires the use of the LuaLaTeX format. A reasonably modern TeX distribution -- such as TeXLive2012, MacTeX2012, or MiKTeX2.9 -- is also required. ***

The package's user guide may be found in the file selnolig.pdf.

To start using this package, at a minimum you should download the *.sty files and the selnolig.lua file to a suitable directory in your personal TeX directory or the localtexmf directory. (The precise location will depend on your TeX distribution.)


