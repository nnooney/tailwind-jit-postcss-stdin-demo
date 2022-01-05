# Tailwind JIT PostCSS from Stdin Bug Demo

This repository is a minimal, complete example of a bug in Tailwind's JIT mode
when processing via stdin as a PostCSS module.

```shell
npm install
npm test
# runs cat tailwind.css | npx --no-install postcss --config ./postcss.config.js
```
