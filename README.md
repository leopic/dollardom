$dom
====
_5k Javascript library for selecting, styling, traversing and animating DOM elements._

$dom was coded by Keith Clark and was once available at http://www.keithclark.co.uk/$dom/.

FAQ
---

### Why ?
I used $dom in a project and wanted to fix one bug. Moreover Keith Clark stopped maintaining this code
and I felt it is still useful nowadays.

### Why $dom ? There are lots of other very good libraries outthere
That's right. For big projects, you can use jQuery, Dojo, ExtJS, Prototype, etc. For mobile projects, there are
jQuery Mobile, jqtouch, Sencha touch, Zepto.js, xui.js.

I needed a _small_ library with support for not only Webkit but also Firefox, IE, etc. I found that $dom
is exactly what I needed at the time.

### Alternative
I do feel [ender.js](http://ender.no.de/) could be a very good alternative.

Development notes
---
The build script needs uglifyjs and node.

On Debian-like systems, these could most probably
be installed with the command :

    aptitude install libnode-uglify

### TODO
* remove the isIE variable and use feature sniffing instead.
* make the library compressable with uglify
(it is not right now, because of the use of IE conditional compilation to compute the previous isIE variable)
* separate the animate part
* write good documentation
* write good tests




