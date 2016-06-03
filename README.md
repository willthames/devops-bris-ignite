# Ignite slides for DevOps Brisbane Meetup 02/06/2016

Basis of slides is [slides.md](slides.md).

To convert slides to HTML:

```
git submodule init
make
```

This uses [pandoc](http://pandoc.org) to [convert from
markdown](http://pandoc.org/README.html#producing-slide-shows-with-pandoc)
to [reveal.js](http://lab.hakim.se/reveal-js/)

The [default.revealjs](default.revealjs) template
is based on the source from pandoc, but with a couple of
tweaks to pass autoSlide timings to reveal.js and allow
CSS overrides through [overrides.css](overrides.css)
