## Archived

Continued at [https://github.com/try-nano/try-nano.github.io/](https://github.com/try-nano/try-nano.github.io/)

## What's this?

Nano is so stupidly easy for anyone to try out, that they just should! This is a simple website made only for that purpose, designed to be as short as possible. 

[Website](https://otonashixav.github.io/try-nano)

In order to keep things simple, it runs on Jekyll and is hosted on Github. 

https://api.nanos.cc/ is used to calculate faucet balance.

## Running locally

Install Ruby and Bundle, then run 

```sh
bundle install
bundle exec jekyll serve
```

## Localization

I've made an example at [https://otonashixav.github.io/try-nano/jp](https://otonashixav.github.io/try-nano/jp). To add a translation, create a new folder for that language e.g. `/jp`, copy `/en/index.md` into the folder and translate it, then update `/lang/index.md` with a link to the translation. Submit a pull request once you're done editing.
