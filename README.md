KSP-tmLanguage
==============

This is a `.tmLanguage` specification for configuration files in [Kerbal Space Program](https://kerbalspaceprogram.com/), including `persistent.sfs` and `part.cfg` files. I developed this for syntax highlighting when editing these files in [Sublime Text](http://www.sublimetext.com/).

`KSP configuration.JSON-tmLanguage` is the JSON "source" for the specification, which can be "compiled" into the XML `.tmLanguage` type with [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev). All the work is done in the JSON, so it includes comments.

To use with Sublime Text select Sublime Text Preferences -> Browse Packages... in Sublime Text, and copy `KSP configuration.tmLanguage` to `Packages/User/`.

[Here's how it looks.](http://i.imgur.com/AZNdorq.png)

I am quite new to regex so I welcome suggestions. It's far from complete.
