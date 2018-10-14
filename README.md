# generate-hash-inline-script

> Generate Hash for Inline Script while using Chrome Extensions due to Content Security Policy (CSP) errpr ❌

## But, why?

Because I faced this problem while making [Meta Preview](https://twitter.com/deadcoder0904/status/1048129409885122560)

## Usage

Just replace the `script` variable in `index.js` with the contents of your inline script & run `index.js`

## Example

If your inline script is like -

```js
<script>alert('Yo Yo Yo!')</script>
```

then replace `script` variable in `index.js` like -

```js
const script = `alert('Yo Yo Yo!')`;
```

& type in terminal

```bash
node index.js
```

Voila, it will copy the hash to the clipboard.

## Credits

All the credits go to https://stackoverflow.com/a/38554505/6141587

I just tweaked a little to copy it to clipboard :)
