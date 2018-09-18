# flexboxgrid2
[![npm version](https://badge.fury.io/js/flexboxgrid2.svg)](https://badge.fury.io/js/flexboxgrid2)

Modern 12 column grid system based on flex property.

→ [Documentation](https://evgenyrodionov.github.io/flexboxgrid2/)

## Motivation
Forked from [kristoferjoseph/flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid) because original project seems abandoned ([kristoferjoseph/flexboxgrid#236](https://github.com/kristoferjoseph/flexboxgrid/pull/236), [kristoferjoseph/flexboxgrid#229](https://github.com/kristoferjoseph/flexboxgrid/pull/229), [kristoferjoseph/flexboxgrid#211](https://github.com/kristoferjoseph/flexboxgrid/pull/211), etc).

## Breakpoints
- `xs`: 0..575px
- `sm`: 576..767px
- `md`: 768..991px
- `lg`: 992..1199px
- `xl`: 1200px+
- `.container` padding: 8px
- `.container` width: $breakpoint - 16px
- `.col-*` padding: 8px

## Install
### yarn
`yarn add flexboxgrid2`

### npm
`npm i -S flexboxgrid2`

# Usage
### webpack
```js
import 'flexboxgrid2'
// or if you use airbnb-config-eslint which explicitly wants .css extension
import 'flexboxgrid2/flexboxgrid2.css'
```

### unpkg.com CDN
```html
<link rel="stylesheet" href="https://unpkg.com/flexboxgrid2@[version]/flexboxgrid2.css">
``` 

Replace `[version]` with current version, f.e. `7.2.1`
