# ascii-modifiers-map

> ASCII Modifiers Map

Nothing more than a mapping of plain alphas to their [bold](https://www.w3.org/TR/MathML2/bold-sans-serif.html) and [italic](https://www.w3.org/TR/MathML2/sans-serif-italic.html) counterparts

# Install

```sh
$ npm install --save ascii-modifiers-map
```

# Usage

```js
import { bold, italic } from 'ascii-modifiers-map'

console.log(bold.a, bold.A, bold[0])

// note: italic does not contain numerics
console.log(italic.a, italic.A)
```

# License

MIT © [Andrew Carpenter](https://github.com/doesdev)
