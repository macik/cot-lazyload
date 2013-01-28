LazyLoad
========

Plugin for Cotonti CMF. Designed for implement images «lazy loading».

Description
-----------

Extends pages with «lazy loading» functionality. It speeds up loading of page with a lot of
images.
With this Extension images on the page are loading only when they appears on screen.
So it is not loaded until you scroll page for certain image had visible.

Features
--------

* Delays loading of images outside a viewport
* Pages containing many images loads faster
* Two different library for your choice
* Control what images to make «lazy»
* Works in browsers with JS switched off (just like «Lazy» switched off)
* Sample page included

Demo page
---------

Sample page included in Extension pack. Just install and open plugin page
(http://www.yoursite.com/lazyload/).

### Comments

Plugin works out from the box. For better results you may setup `height` and `width` attributes
for you images. In that case content structure won't be rearranges during «lazy» load.



### How extension works

Extension parses page content for `img` tags checks `src` attribute and substitute it with
dump (transparent) image. When page loads script processes that `img` tags to check is it visible 
at this moment or not. As image become visible it loads as standard one.


Install
-------

* Unpack, copy files to root folder of your site.
* Install via Admin → Extensions menu (`Administration panel → Extensions`)
* Checks setting in config (`Administration panel → Extensions → LazyLoad → Configuration`).

### Comments

To see this Extension in action - open «LazyLoad» plugin page. There you can see sample page 
with multiple «lazyload» images.


References
----------

* [Cotonti.com](http://Cotonti.com/) -- Home of Cotonti CMF
* [LazyLoad on GitHub](http://macik.github.com/cot-lazyload/) -- LazyLoad Page
* [Demo of LazyLoad](http://macik.github.com/cot-lazyload/demo.html) -- LazyLoad demopage


