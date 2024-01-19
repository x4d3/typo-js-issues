# Typo.js Issues

This is a test page to reproduce issues with the [typo-js](https://github.com/cfinke/Typo.js) library.

It loads a french dictionary from  [fr_FR.aff](fr_FR.aff) and [fr_FR.dic](fr_FR.dic).

- First it shows that calling `typo.suggest("ok")` throws an error.
- Second it demonstrates that `typo.suggest("Anticonstiutni2onlleemnt")` takes more than 25 seconds and block the browser.

https://x4d3.github.io/typo-js-issues/
