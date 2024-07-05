# gh-fs

> [!Important]
> Work in progress.

GitHub CLI extension for mapping repo owners/orgs to your filesystem.

## Idea

* Set a default clone destination folder for your personal account (`bswck`)
  `gh fs set bswck ~/Projects`

  `cd ~/ && gh repo clone slothy` should now clone into `~/Projects/slothy`

* Set a default clone destination folder for organization `coherent-oss`
  `gh fs set coherent-oss ~/Coherent`

  `cd ~/ && gh repo clone coherent-oss/build` should now clone into `~/Coherent/build`

