
# zalxon / theme

**lightweight Theme-UI configuration for Zalxon websites**

[![GitHub][github-badge]][github]
[![Build Status]][actions]
![MIT License][]
![NPM Version][]

[github]: https://github.com/zalxon/theme
[github-badge]: https://badgen.net/badge/-/github?icon=github&label
[build status]: https://github.com/zalxon/theme/actions/workflows/main.yml/badge.svg
[actions]: https://github.com/zalxon/theme/actions/workflows/main.yml
[mit license]: https://badgen.net/badge/license/MIT/blue
[npm version]: https://badgen.net/npm/v/@zalxon/theme

## usage

To use, import into your package

```js
import theme from '@zalxon/theme'
```

and then either use it directly or extend it for further customization

```js
export default {
  ...theme,
  styles: {
    ...theme,
  },
}
```

## license

All the code in this repository is [MIT](https://choosealicense.com/licenses/mit/) licensed, but we request that you please provide attribution if reusing any of our digital content (graphics, logo, articles, etc.).

## about us

Zalxon is a non-profit organization that uses data and science for healthcare action. We aim to improve the transparency and scientific integrity of healthcare solutions with open data and tools. Find out more at [zalxon.com](https://zalxon.com/) or get in touch by [opening an issue](https://github.com/zalxon/theme/issues/new) or [sending us an email](mailto:hello@zalxon.com).
