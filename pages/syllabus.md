---
layout: page
title: about this course // syllabus
description: Syllabus
---

This is an example course (page)!

## Description of the set-up

This is an example class site.
To add new pages, just put them, in markdown format, in this directory (`pages/`);
copy the existing format (note the YAML header).

This is *not* using the now-deprecated github-pages publication method;
instead it has a github action that publishes it; this is under `.github/workflows/jekyll.yml`.

## Viewing the site locally

Install jekyll and run `bundle init` and then `bundle install`.
(You only have to do this once; if you change or add things to the Gemfile you might have to do `bundle install` again though.)

Then, to build the site (to the subdirectory `_site/`) run `bundle exec jekyll build`.
To serve it up on a local webserver, run `bundle exec jekyll serve`.

## Customizing

The theme "minima" (the default!) and is a "theme gem" meaning most of the files live in the gem,
unless they're overwritten by local copies.
Thus, the files in `_includes/` and `_layouts` I copied from the location I found by doing `bundle info --path minima`
and modifying somewhat.
