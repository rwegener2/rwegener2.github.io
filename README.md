# Forty - Jekyll Theme

A Jekyll version of the "Forty" theme by [HTML5 UP](https://html5up.net/).  

![Forty Theme](assets/images/forty.jpg "Forty Theme")

# How to Use

For those unfamiliar with how Jekyll works, check out [jekyllrb.com](https://jekyllrb.com/) for all the details, 
or read up on just the basics of [front matter](https://jekyllrb.com/docs/frontmatter/), [writing posts](https://jekyllrb.com/docs/posts/), 
and [creating pages](https://jekyllrb.com/docs/pages/).

Simply fork this repository and start editing the `_config.yml` file!

> NOTE: GitHub Actions is required to deploy to GitHub Pages because GitHub [refuses to update their version of Jekyll](https://github.com/github/pages-gem/issues/651).

## Running

Prerequisite: install jekyll (`gem install jeykll` with the proper version of ruby installed: ruby version >= 3.0).

1. (if not previously done) `bundle config set path 'vendor/bundle'`
2. Install packages with `bundle install`
3. Start website with `bundle exec jekyll serve --watch`

Note: with ruby v4 needed to manually add logger (`bundle add logger`)

# Deployment Notes

https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site

# Added Features

* **[Formspree.io](https://formspree.io/) contact form integration** - just add your email to the `_config.yml` and it works!
* Use `_config.yml` to **set whether the homepage tiles should pull pages or posts**, as well as how many to display.
* Add your **social profiles** easily in `_config.yml`. Only social profiles buttons you enter in `config.yml` show up on the site footer!
* Set **featured images** in front matter.

# Credits

Original README from HTML5 UP:

```
Forty by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Forty, my latest and greatest addition to HTML5 UP and, per its incredibly
creative name, my 40th (woohoo)! It's built around a grid of "image tiles" that are
set up to smoothly transition to secondary landing pages (for which a separate page
template is provided), and includes a number of neat effects (check out the menu!),
extra features, and all the usual stuff you'd expect. Hope you dig it!

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		background-size polyfill (github.com/louisremi)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
```

Repository [Jekyll logo](https://github.com/jekyll/brand) icon licensed under a [Creative Commons Attribution 4.0 International License](http://choosealicense.com/licenses/cc-by-4.0/).

## Photo links
- [Chesapeake Bay Bridge](https://unsplash.com/photos/a-large-bridge-spanning-over-a-large-body-of-water-jY8TXnAfXhs) by Max Shein via Upsplash
- [ICESat-2](https://images.nasa.gov/details/NHQ201809130019) by NASA
- [SARP Coding Instruction](https://unsplash.com/photos/a-group-of-people-holding-hands-on-top-of-a-tree-DNkoNXQti3c) Photo by Shane Rounce via Upsplash
- UMD teaching https://unsplash.com/photos/an-empty-classroom-with-wooden-desks-and-windows-dFohf_GUZJ0

# Original authors

This package was forked from @andrewbanchich https://github.com/andrewbanchich/forty-jekyll-theme
