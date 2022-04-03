# Normalize CSS

Custom CSS which I use for resetting all default styles.

## Use with a CDN

To rapidly include the minified production file in your webpage

```html
<link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/gh/KunalTanwar/normalize/css/normalize.min.css"
/>
```

### An optional version

_`normalize.inter.min.css`_ in which [Inter](https://github.com/rsms/inter) is set as default font with fallbacks.

```html
<link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/gh/KunalTanwar/normalize/css/normalize.inter.min.css"
/>
```

## Browser Support

-   Chrome
-   Edge
-   Firefox ESR+
-   Opera
-   Safari 8+

### Note

You can change `.browserslistrc` for supporting more previous versions of browsers. And run following commands :

```bash
yarn compile
# or
npm compile

yarn prefix
#or
npm prefix
```

Don't forget to run `yarn install` or `npm install` in order to install dependencies.
