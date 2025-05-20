# WordPress Glossaries for Translation Tools

This repository contains JSON-formatted glossaries for a wide range of locales, originally extracted from the [WordPress Translate project](https://translate.wordpress.org/). These glossaries are intended to support the development of translation tools, plugins, and AI systems by providing standardized terminology.

## Purpose

This repository can be used to:

* Enhance machine translation (AI) with consistent glossary terms
* Improve translation quality in WordPress plugins or themes
* Integrate into localization workflows or custom translation tools
* Aid in building glossaries for translators and translation memory systems

## Data Format

Each file is named by its [WordPress locale code](https://make.wordpress.org/polyglots/teams/) and contains entries in the following format:

```json
"batch": {
  "noun": "lote",
  "adjective": "em lote"
}
```

This format helps disambiguate words that may change meaning depending on their part of speech.

## Contributing

We welcome improvements to these glossaries!

* Fix existing translations
* Add new entries for existing locales
* Submit glossaries for missing locales

Please open a pull request or start a discussion if you’d like to contribute.

## License

This repository is licensed under the [GNU General Public License v3.0 (GPL-3.0)](./LICENSE).
