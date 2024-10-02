# Overview

This Hugo theme is called japan-biz.  It is based on Based on html5up’s [Spectral](https://html5up.net/spectral) theme.  The configuration used is based on a project by sbruder for a customer project this person did.  The original source is https://git.sbruder.de/kegelschiene/site , for the site: [kegelschiene.net](https://kegelschiene.net/en/).

Our team in Japan will maintain this to add features specific to Japanese market (SNS links appropriate to Japan, etc.) but these things are in the works.  Please file an issue if you need specific features.

## Motivation

There is a particular style for Japanese "business" websites.  Say what you like about Japanese UX ... the sites follow a particular design pattern.  One feature often missing in Japanese websites is a proper implementation of localization for English. 

Sometimes this will be done in earnest, however, it will usually mean a scaled down set of information, and not the entire site in English.  Very frustrating to an English speaking audience.  A second failing of localization to English is just relying on Google translate.  While generally very accurate, it can fail to translate certain ideas that only exist in Japanese.  This is where it helps to have a team that can easily go between two languages, and also understands the particulars of each market.  If you feel you need help in this area, feel free to contact us via our website at https://iotoneai.site.

## Installation

If this is your first hugo page, please read the [Basic Usage of Hugo](https://gohugo.io/getting-started/usage/) article.

Clone this repo or download the zip, place it inside of the `themes` directory
of your hugo site and use the `config.toml` file located in exampleSite as a
starting point.

## Building

Testing
    hugo --serve

Generate


    hugo -d ../public

If using https, you will need to specify the domain and https URI:

hugo -d ../public -b https://mygreat.site


## Examples

Original information from upstream project ...

If you want to have a look at a real life installation, feel free to explore
the [repo of
kegelschiene.net](https://git.sbruder.de/kegelschiene/site). It also includes
the configuration for a multilingual site.

For a minimial setup, check out the [exampleSite](exampleSite) directory. Its latest live build can be seen at <https://sbruder.github.io/spectral/>.

## License

This theme is licensed under the terms of the Creative Commons Attribution 3.0 Unported (like html5up’s original theme). See the LICENSE.md file for more information on this.
