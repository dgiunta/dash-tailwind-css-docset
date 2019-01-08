# Tailwind CSS Dash Docset

This is a barebones Dash docset creator for the [Tailwind
CSS](https://www.tailwindcss.com)
[docs](https://www.tailwindcss.com/docs).

## Installation

1. [Install the `dashing` command line tool](https://github.com/technosophos/dashing#install) helper for building the docset: `brew install dashing` if you're on Mac OS X.

2. Install `wget`: `brew install wget` if you're on Mac OS X.

2. To generate the docset, you can run `./bin/update` which will download all of the raw html docs using `wget` and run `dashing build`. That will create the docset files which you can add to your Dash.app.
