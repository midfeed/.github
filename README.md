# `.github` — midfeed organisation defaults

This repository hosts the public-facing configuration for the
[**midfeed**](https://github.com/midfeed) GitHub organisation. It is
intentionally small. Files here are picked up by GitHub as either
the org profile page or as fall-through defaults for any repo in
the org that doesn't ship its own version.

## What's in here

| Path | Purpose |
|---|---|
| [`profile/README.md`](./profile/README.md) | Renders on the public organisation page at [github.com/midfeed](https://github.com/midfeed). |
| [`SECURITY.md`](./SECURITY.md) | Vulnerability disclosure policy. Surfaces as the **Security** tab on every repo in the org that doesn't override it. Reports go to `dev@midfeed.com`. |

## Working with this repo

This repository is **public by design** — GitHub requires it to be
public for the profile page and community-health fall-throughs to
render. Everything else under the `midfeed` org stays private.

When editing, please:

1. Keep the language brand-aligned with [midfeed.com](https://midfeed.com).
2. Avoid mentioning private infrastructure, internal hostnames, or
   product specifics that aren't already public on the marketing site.
3. Preview Markdown locally before opening a PR — the profile page
   is the first impression visitors get of midfeed on GitHub.

