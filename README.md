# Theme B2Bware Starter Kit

Blank-canvas starter for a **custom** B2Bware storefront theme.

- **No** default Blade pages/partials/layouts — you build those.
- **Yes** the full authoring contract under [`theme/docs/`](theme/docs/).
- We **recommend [Cursor](https://cursor.com)**; `.cursor/rules` points agents at
  the right docs. Other AI tools: see [`AGENTS.md`](AGENTS.md).

## Quick start

1. Use this template / fork / download ZIP → rename to `Theme_B2Bware_<Client>`.
2. Edit `theme/theme.json` (`name`, `slug`, `author`, `version`).
3. Fill [`docs/CLIENT-CONTEXT.md`](docs/CLIENT-CONTEXT.md) (staging URLs, brand notes).
4. Build Blade under `theme/layouts|partials|components|pages` using `theme/docs/`.
5. `./scripts/build-zip.sh` → upload `dist/<slug>-<version>.zip` in the admin Themes page.

## Want the full default theme instead?

Use **[theme_b2bware_default](https://github.com/SyncSpider-GmbH/theme_b2bware_default)** —
same project layout, but with every layout, partial, component and page already built, so you
can restyle instead of starting over.

## Keeping docs fresh

`theme/docs/` is updated here whenever the theme contract changes. On an old fork, refresh
the topic pages from the **live public wiki** — no credentials needed, and your
Blade/CSS/`theme.json`/`README.md`/`CHANGELOG.md` are never touched:

```bash
./scripts/update-theme-docs.sh
```

That pulls https://github.com/SyncSpider-GmbH/b2bware-documentationai-wiki
(`advanced/storefront-themes/`).

Live docs: https://b2bware.documentationai.com/advanced/storefront-themes
