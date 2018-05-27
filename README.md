# What is this?
This is a set of configurations for [Karabiner](https://pqrs.org/osx/karabiner/)'s 'complex_modifications' to make pressing two keys work as modifier keys following [gabrielelana's engelbart configuration](https://github.com/gabrielelana/engelbart).

# How it works?
When you simultaneously press two keys they will be mapped to another (convenient) key.

* `D+F` or `J+K` to `CONTROL`
* `S+D` or `K+L` to `OPTION` (or `META`, `ALT`)
* `E+F` or `J+I` to `SHIFT`
* `D+V` to `TAB`
* `K+N` to `ESCAPE`
* `H+J` to `DELETE`

# Installation
* Install [Karabiner](https://pqrs.org/osx/karabiner/)
* Import the `twokeys.json`: [import](karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/hsjin/twokeys/master/twokeys.json)
    * As of version 12.0, Karabiner does not provide a GUI to import a custom complex modification configuration (as 'Open private .xml' in previous versions)
    * Instead, configurations are imported using Apple URL Scheme: open the `URL` of the `json` file containing configurations in a browser using `karabiner://karabiner/assets/complex_modifications/import?url=<JSON_URL>`
    * Use the `URL` of `twokeys.json` in this repository: `https://raw.githubusercontent.com/hsjin/twokeys/master/twokeys.json`
    * See [https://github.com/pqrs-org/KE-complex_modifications#local-testing](https://github.com/pqrs-org/KE-complex_modifications#local-testing)

