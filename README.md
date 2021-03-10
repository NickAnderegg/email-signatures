# email-signatures

## Minifying HTML

To minify the HTML in a way that is compatible with most email clients, use [HTML Minifier](https://www.npmjs.com/package/html-minifier) with the following settings:

```bash
html-minifier --collapse-whitespace --remove-comments path/to/full/file.html
```

Using additional minifier settings can possibly break the rendering in some email clients.
