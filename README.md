# Dotrocks
`dotrocks` is a theme for [Pelican](https://github.com/getpelican/pelican). It a minimal feature rich fork of [Medius](https://github.com/onur/medius) theme.

Live usage over http://granitosaurus.rocks:

![Screenshot](./screenshot.png?raw=true)


# Features

* Minimal, clean, fast and mobile friendly design.
* SEO optimized - meta, og etc.
* Tag and category oriented organization
* Comment support via http://uterranc.es

# Settings

Dotrocks support most of pelican default config setting such as `SOCIAL`, `FOOTERITEMS` etc.

Additional settings for addons:

* Comments:
    * `UTTERANCES_REPO`\* - github repo, e.g. `user/repo`
    * `UTTERANCES_LABEL[comments]` - label for issues created by utterances
    * `UTTERANCES_THEME[github-light]` - utterances theme.
    
    note: issue name is set to slug or url if slug is not present

* Analytics:
    * `GOOGLE_ANALYTICS` - token for google analytics
    * `GAUGES` - token for gaug.es analytics

# Article Properties

Dotrocks implement additional article properties:

* `add_toc: True` with `pelican-toc` plugin will add tables of content after between intro text and first header.
