## wabisabitravel

Hosted on Github Pages.

## History

Static site generated from a deployed Ghost site using:

`wget --no-clobber --convert-links --random-wait -r -p --level 3 -E -e robots=off -U mozilla https://wabisabitravel.com/`

Then find & replace some issues with mangled jpg / jpeg image extensions in responsive tags.

## Deploying

`git subtree split --branch gh-pages --prefix wabisabitravel.com/`
