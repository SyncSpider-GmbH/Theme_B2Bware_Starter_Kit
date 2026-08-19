# Theme source

This folder is what gets zipped and uploaded in the B2Bware admin **Themes** page.

## Authoring guide

Everything you need to build a theme is in **[`docs/`](docs/)**. Start at
**[`docs/README.md`](docs/README.md)** — the load matrix for you (or your AI assistant).
Always read [`docs/hard-rules.md`](docs/hard-rules.md) first.

> **Latest version.** The copy in `docs/` shipped with this repo and may be outdated. The
> authoritative guide is online:
> https://b2bware.documentationai.com/advanced/storefront-themes
> Changelog: https://b2bware.documentationai.com/changelog

## Layout (starter kit)

You add these as you build — nothing is pre-shipped in the starter kit:

```
theme.json      metadata (required)
docs/           authoring guide (bundled for offline / AI context)
layouts/        shop + auth shells
partials/       header, footer, cart sections, account, …
components/     product card, price, buttons, …
pages/          products, product, cart, checkout, account/*, …
assets/         css / js / images / fonts
```

For the full default theme (all folders populated), use
**[theme_b2bware_default](https://github.com/SyncSpider-GmbH/theme_b2bware_default)**.
