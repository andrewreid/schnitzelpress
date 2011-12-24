# Schreihals

Everybody should be developing their own blogging engine for hackers, so here's mine.
Documentation is pretty minimal at the moment, so for now, how about a list of
overall design goals?

## Overall Design Goals

* Minimal code design.
* Author your blog through git, using Markdown and friends.
* Near-zero boilerplate code in your blog project. (It's all in the gem.)
* Theme support through gems.
* No static document generation. (Not interested, there are enough engines out there that do this.)
* HAML and SASS support out of the box.

## Usage

TODO: soon

## Stuff

Just a list of keywords I need to write about:

* Configuration
* Automatic `date` and `slug` recognition
* `status` attribute and drafts
* `disqus` and `disqus_identifier` attributes
* Using different post formats (markdown, textile, haml etc.)
* pages (= posts without dates)
* deployment (Heroku!)
* code highlighting
* `google_analytics_id`
* `link`
* `read_more`
* `schreihals create NAME`
* `schreihals post TITLE`

## Version History

### 0.0.2

* Fix various stupid bugs from the initial release, including the broken example app. Duh!
* When a post or page could not be found, we now display a proper 404 page (with correct status code.)

### 0.0.1

* Initial release.
