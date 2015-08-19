---
layout: article
title: "MISC | How to Survive Research"
comments: true
---

## Others


* Command Line Recording: [asciinema](https://asciinema.org/)

* [QR Code Generator](https://www.unitag.io/qrcode)

## Terminal

1. [plot in terminal](https://github.com/glamp/bashplotlib)


### Graph Making

1. [bashplot](https://github.com/glamp/bashplotlib): plot in terminal.


### HTML

Use [Animate.CSS](https://github.com/daneden/animate.css) to animate contents


### Free Multimedia

Free high resolution images:

1. [Unsplash](https://unsplash.com/)


### Migrating Wordpress to Static

The following command can mirror a whole website including a wordpress into a static html site locally.

```
# Mirror website to a static copy for local browsing.

# This means all links will be changed to point to the local files.

# Note --html-extension will convert any CGI, ASP or PHP generated files to HTML (or anything else not .html).

wget --mirror -w 2 -p --html-extension --convert-links -P <dir> http://www.yourdomain.com
```
But this will get a static site with absolute links. To get a site that works as relative links for wordpress, use this plugin in first:

* [staticpress](https://github.com/megumiteam/staticpress)

