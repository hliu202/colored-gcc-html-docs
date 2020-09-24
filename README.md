Colored GCC docs with customized css style. Currently:

1. only the purple.css style is added.
2. only [gcc internal docs](https://gcc.gnu.org/onlinedocs/gccint/index.html#Top) are added. Version is 10.2.

## How to use

Open `gccint/index.html` or `gcc-internal-docs.html` with your favorable web browser.

## How to change style

```bash
rm gccint/css/style.css
ln -s <path-to-your-css-style> gccint/css/style.css
```

