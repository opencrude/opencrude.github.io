# opencrude.github.io

This repository publishes <https://opencrude.github.io/>. It holds no site source.

The website source is in [`opencrude/crude`](https://github.com/opencrude/crude) under `site/`.
See the [website guide](https://github.com/opencrude/crude/blob/master/docs/guides/website.md).

To deploy, push the site change to `opencrude/crude`, then run:

```bash
gh workflow run pages.yml -R opencrude/opencrude.github.io
gh run watch -R opencrude/opencrude.github.io
```
