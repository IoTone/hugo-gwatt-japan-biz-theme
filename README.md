# Overview

This Hugo theme is called japan-biz.  When we looked around there didn't seem to exist any Hugo templates other than a blog designed for Japanese business websites.  It is written from scratch, but inspired in spirit by the MicroCMS Japan business theme for nestJS : https://github.com/microcmsio/nextjs-simple-corporate-site-template .

Our team in Japan will maintain this to add features specific to Japanese market (SNS links appropriate to Japan, etc.) but these things are in the works.  Please file an issue if you need specific features.

## Motivation

There is a particular style for Japanese "business" websites.  Say what you like about Japanese UX ... the sites follow a particular design pattern.  One feature often missing in Japanese websites is a proper implementation of localization for English. 

Sometimes this will be done in earnest, however, it will usually mean a scaled down set of information, and not the entire site in English.  Very frustrating to an English speaking audience.  A second failing of localization to English is just relying on Google translate.  While generally very accurate, it can fail to translate certain ideas that only exist in Japanese.  This is where it helps to have a team that can easily go between two languages, and also understands the particulars of each market.  If you feel you need help in this area, feel free to contact us via our website at https://iotoneai.site.

## Demo

- https://iotone.github.io/hugo-gwatt-japan-biz-theme/en/

## Installation

If this is your first hugo page, please read the [Basic Usage of Hugo](https://gohugo.io/getting-started/usage/) article.  Note: Hugo v0.135.0 or greater is needed.  Older versions may not work.

Clone this repo or download the zip, place it inside of the `themes` directory
of your hugo site and use the `config.toml` file located in exampleSite as a starting point.

Replace the content directory with your own content in the /content/en and /content/ja folders

## Building

Generate


    hugo -d ../public

If using https, you will need to specify the domain and https URI:

    hugo -d ../public -b https://myurl.co.jp

## Contributors

- @garethwatt
- @truedat101
- http://iotoneai.site
- gohugo.io (thanks for the platform)

## Support

If you have specific problems or questions, please file an issue, or offer a pull request.

If you need expert customization and evelopment of a localized site for your business or project, please contact us.  We have an expert crew with native english and japanese speakers available.  If you has needs for more languages, we can support a plan for additional localization of languages.

## License

MIT/X
