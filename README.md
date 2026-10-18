# dsh-market-index

A [DSH plugin market index](https://deepseek-harness.github.io/deepseek-harness/en/guide/plugin-market) (format 1) for the **Discover** tab of DeepSeek Harness (`Plugins → More → Custom plugin markets → Discover`).

It lists the community plugin market package [`dshmarket`](https://www.npmjs.com/package/dshmarket) ([dshmarket.com](https://dshmarket.com), [source](https://github.com/dsh-market/dsh-market)).

## Index URL

```text
https://raw.githubusercontent.com/archainur/dsh-market-index/main/index.json
```

Add it in DSH via **Plugins → Discover → Add index source**, or configure it for a profile:

```yaml
- id: plugin-market
  config:
    indexes:
      - https://raw.githubusercontent.com/archainur/dsh-market-index/main/index.json
```

## Contents

- `dshmarket@1.66.37`
- `dshmarket@1.66.32`

The file is served as-is by `raw.githubusercontent.com` (HTTP 200, no redirect) and follows DSH's plugin market index format 1. Install sources are plain npm (`dshmarket@<version>`); DSH re-checks the package's own compatibility at install time.

Generated metadata comes from the npm registry and the plugin's public repository. Nothing here is affiliated with DeepSeek.
