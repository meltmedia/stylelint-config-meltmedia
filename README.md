# stylelint-config-meltmedia

This [stylelint](https://stylelint.io) config contains rules specific to how we write our CSS at [meltmedia](https://meltmedia.com). It's flexible enough to use for most projects, with rules used mostly to catch common errors, enforce explicit declarations, and ensure best practices. The ruleset was created by [the HTML & CSS Guidelines team](https://github.com/orgs/meltmedia/teams/html-css-guidelines), please reach out with any suggestions for rules or feedback on your usage.

To see the rules that this config uses, please read [the config itself](/index.js).

## Installation

```bash
npm install github:meltmedia/stylelint-config-meltmedia --save-dev
```

## Usage

Create a `.stylelintrc` file at the base of your project:

```json
{
  "extends": "stylelint-config-meltmedia"
}
```

### Extending the config

Simply add a `"rules"` key to your config, then add your overrides and additions there.

For example, to change the `indentation` to tabs:

```json
{
  "extends": "stylelint-config-meltmedia",
  "rules": {
    "indentation": "tab"
  }
}
```
