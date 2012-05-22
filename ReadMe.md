# Font Stash: Dynamic font glyph cache for OpenGL

Quick and simple Addon wrapping [Font-Stash](https://github.com/akrinke/Font-Stash). 

"Font Stash enables easy string rendering in OpenGL applications. It supports truetype fonts and UTF-8 encoded localized strings. All glyphs are cached in OpenGL texture atlases. Font rasterization is done using Sean Barrett’s stb_truetype.h."

I made tiny modifications to render text flipped vertically, to play nicer in the OpenFrameworks universe.

Font Stash was originally created and [published](http://digestingduck.blogspot.com/2009/08/font-stash.html) by [Mikko Mononen](http://digestingduck.blogspot.com).

## License

ofxFontStash.cpp and ofxFontStash.h have been created by Oriol Ferrer Mesià and released under [MIT license](http://www.opensource.org/licenses/mit-license.php).

	Copyright (c) 2012 Oriol Ferrer Mesià
	
	Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
	
	The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
	
	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

The files fontstash.c, fontstash.h and main.c are licensed unter the zlib license:

    Copyright (c) 2011 Andreas Krinke andreas.krinke@gmx.de
    Copyright (c) 2009 Mikko Mononen memon@inside.org

    This software is provided 'as-is', without any express or implied
    warranty.  In no event will the authors be held liable for any damages
    arising from the use of this software.
    Permission is granted to anyone to use this software for any purpose,
    including commercial applications, and to alter it and redistribute it
    freely, subject to the following restrictions:
    1. The origin of this software must not be misrepresented; you must not
       claim that you wrote the original software. If you use this software
       in a product, an acknowledgment in the product documentation would be
       appreciated but is not required.
    2. Altered source versions must be plainly marked as such, and must not be
       misrepresented as being the original software.
    3. This notice may not be removed or altered from any source distribution.

For UTF-8 decoding, Font Stash uses Björn Höhrmann's [Flexible and Economical UTF-8 Decoder](http://bjoern.hoehrmann.de/utf-8/decoder/dfa/) (included in fontstash.c).
His code is licensed under the MIT license:

    Copyright (c) 2008-2009 Bjoern Hoehrmann <bjoern@hoehrmann.de>

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
    
Finally, Font Stash uses Sean Barrett's public domain truetype font rasterizer [stb_truetype.h](http://nothings.org/).

