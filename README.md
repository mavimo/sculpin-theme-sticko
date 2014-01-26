# Porting of Sticko theme

![content list](https://raw2.github.com/mavimo/sculpin-theme-sticko/gh-pages/sample/post-list.png)
![content page](https://raw2.github.com/mavimo/sculpin-theme-sticko/gh-pages/sample/post-content.png)
![page with menu open](https://raw2.github.com/mavimo/sculpin-theme-sticko/gh-pages/sample/menu.png)

## About this theme

This is a porting of [sticko](http://sticko.apps.runkite.com/), a clean, modern, **responsive** and **free** theme for the emerging -and absolutely amazing- blogging platform called [Sculpin](http://sculpin.io).

I really hope you like it and feel free to use this theme for whatever purpose you want.

### Features
* Full responsive.
* Lightweight yet beautiful.
* Google+ Comments on Posts.
* Off-canvas navigation.
* Author info outside loop across the whole theme.
* Loading indicator.
* Icon fonts - support for Retina Display/High pixel density screens.
* SCSS source files for further modifications.

### Installation

Sculpin can automatically install this theme for you by adding the following to
your `sculpin.json`:

```json
{
    "repositories": [
        {
            "type": "vcs",
            "url": "git@github.com:mavimo/sculpin-theme-stickio.git"
        }
    ],
    "require": {
        "mavimo/sculpin-theme-stickio": "dev-master"
    }
}
```

Then execute sculpin update, this download and move theme in the right folder.

To enable the theme for the current site edit the ``àpp/config/sculpin_kernel.yml``` file and add:

```
sculpin_theme:
  theme: mavimo/sculpin-theme-sticko
```

### Configuration

This theme support a large set of configurations, all this will be placed in ```sculpin_site.yml```. You can copy and change values from the following sample:

```
title: Theme Demo
subtitle: To Get You Started
cover: http://farm8.staticflickr.com/7378/9495248550_fc2822fd06_h.jpg
social:
  twitter: http://twitter.com/mavimo
  facebook: http://www.facebook.com/marco.moscaritolo
  googleplus: http://plus.google.com/+MarcoVitoMoscaritolo
  flickr:
  linkedin: http://www.linkedin.com/in/mavimo
  pinterest:
  vimeo:
  github: http://github.com/mavimo
  dribbble:
  stumbleupon:
  lastfm:
  rdio:
  youtube:
author:
  image: https://lh3.googleusercontent.com/-i5zt2mRDPTk/AAAAAAAAAAI/AAAAAAAAANI/rZluj1QTwTc/photo.jpg
  name: Marco Vito Moscaritolo
  bio: Developer, technoloy lover.. and chemistry
  location: Bergamo, Italy
```

### Editing CSS/SCSS files.

**Sticko** is developed on top of [Sass](http://sass-lang.com/install) and [Compass](http://compass-style.org/install), which means that you are going to need both running on your own machine; follow both guides to set up the proper environment.


## Get in touch

If by any reason you need/want to get in touch with me, feel free to [drop me an email](mailto:marco@mavimo.org) or find me on [Facebook](http://www.facebook.com/marco.moscaritolo) and [Twitter](http://www.twitter.com/mavimo).

## Licence
[CreativeCommons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)





