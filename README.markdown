Monokai for Visual Studio 2008
==============================

A Visual Studio 2008 Color Theme
--------------------------------

Upon not finding an existing Visual Studio implementation of [Wimer Hazenberg][2]'s excellent [TextMate][5] theme, [Monokai][1], I was certain that either I have strange taste, or the entire .NET development community has no taste.  I'm going with the latter, you chumps.

This vssettings file implements most of the original theme as closely as possible, taking into account that VS does not provide as many contextual elements for syntax coloring as TextMate.  In such cases, the theme tries to adhere to the spirit of Monokai rather than the letter.

Notes
-----
* Using this theme without having [Consolas][3] installed is a waste of time
* Designed mostly for web work.  Not yet tested/optimized for XAML, etc.  Feel free to improve it!
* This theme was designed on an XP box with ClearType enabled.  Depending on your version of 
Windows/ClearType and your monitor, you may want to embolden or un-embolden the font.

Screenshots
-----------

**C#**  
![JavaScript](http://github.com/mmonteleone/monokai-vs/raw/master/screenshots/csharp.png)

**JavaScript**  
![JavaScript](http://github.com/mmonteleone/monokai-vs/raw/master/screenshots/javascript.png)

Installation
------------

Pretty standard:

From Visual Studio, select  Tools > Import and Export Settings and follow the wizard to import monokai.vssettings

This vssettings file only contains font and color data, but do please back up your settings anyway.  

Credit
------

Copyright 2009 [Michael Monteleone][4]

Based on the original [TextMate Theme][1] by [Wimer Hazenberg][2]

License
-------

The MIT License

Copyright (c) 2009 Michael Monteleone

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

[1]: http://www.tmthemes.com/theme/Monokai/ "Monokai TextMate Theme"
[2]: http://monokai.nl/ "Wimer Hazenberg"
[3]: http://www.microsoft.com/DOWNLOADS/details.aspx?familyid=22E69AE4-7E40-4807-8A86-B3D36FAB68D3&displaylang=en "Consolas"
[4]: http://michaelmonteleone.net "Michael Monteleone"
[5]: http://macromates.com/ "TextMate"