# vixenslide #

Live theme preview available at [zackblea.ch](http://zackblea.ch).

This is a modified version of foxslide, a preview of which can be found at [AdrianArtiles.com](http://www.AdrianArtiles.com). In this fork I have made some small changes to the alignment and placement of text and icons as to bring it more in line with my tastes in design. I've also made some small changes to the back end code, which I hope make the site easier to generate.
Foxslide is a theme built for [Octopress](http://Octopress.org) that is a work in progress with inspirations from all over the web. Built on top of [bootstrap](http://twitter.github.com/bootstrap/) and [html5 boilerplate](http://html5boilerplate.com/), and has SEO consideratins along with instagram and twitter widgets out of the box.

## Installation ##

````
$ cd yourOctopress
$ git submodule add https://github.com/zackbleach/vixenslide .themes/vixenslide
$ git submodule update --init
$ rake install['vixenslide']
$ rake generate
````

### Grab the latest updates ###

````
$ cd yourOctopress
$ git submodule update
# regenerate, make changes, etc...
````

### Alternate installation without git submodule ###
````
$ cd yourOctopress
$ git clone https://github.com/zackbleach/vixenslide .themes/vixenslide
$ rake install['vixenslide']
$ rake generate
````

## Pull-Requests Welcomed! ##

This is a first draft and can definitely be improved on. Pull requests are very much welcomed and desired!

### Demo ###

This is the theme currently powering the site at [zackblea.ch](http://zackblea.ch)
