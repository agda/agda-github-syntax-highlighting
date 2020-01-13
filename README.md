Syntax highlighting for Agda
============================

This repository contains (rudimentary) syntax highlighting for Agda, for use on GitHub.

To make a change to this grammar:
- change `Agda.yml` accordingly (see the [documentation of the grammar format](https://macromates.com/manual/en/language_grammars)),
- test your changes on [Lightshow](https://github-lightshow.herokuapp.com),
- generate the `Agda.tmLanguage` file using [this script](https://github.com/asciidoctor/sublimetext-asciidoc/blob/master/script/yaml-to-plist),
- commit and push your changes (or send a pull request to this repository),
- wait patiently for the next release and deployment of linguist on GitHub, the changes here will be taken into account automatically.
