# gh-fs

> [!Important]
> Work in progress.

GitHub CLI extension for mapping repo owners/orgs to your filesystem.

## Idea

* Set a default clone destination folder for your personal account (`bswck`).<br>
  `gh fs set bswck ~/Projects`

  `gh repo clone slothy` from anywhere on your system should now clone into `~/Projects/slothy`.

* Set a default clone destination folder for organization `coherent-oss`.<br>
  `gh fs set coherent-oss ~/Coherent`

  `gh repo clone coherent-oss/build` from anywhere on your system should now clone into `~/Coherent/build`.

* Set a default clone destination folder for unknown orgs `?`.<br>
  `gh fs set ? ~/Contrib`

  `gh repo clone pandas-dev/pandas` from anywhere on your system should now clone into `~/Contrib/pandas`.

Or maybe should this be a feature of [pj](https://github.com/coherent-oss/pj)?

