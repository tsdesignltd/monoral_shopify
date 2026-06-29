# MONORAL Shopify Site Handoff

## Project

- Store: https://monoral-2.myshopify.com
- Theme: Rise
- Live theme ID: `153165660354`
- GitHub: https://github.com/tsdesignltd/monoral_shopify
- Recommended local folder name: `monoral-theme-rise-live`

## Completed work

- Made each PRODUCTS card on the home page clickable.
- Added the Outlet card to PRODUCTS.
- Used `assets/factory-outlet.png` for the Outlet card.
- Added Outlet to the desktop and mobile PRODUCTS menus.
- Updated the desktop header layout so the logo and right-side icons follow the window width.
- In `sections/header.liquid`, `.header.monoral-header.page-width` uses:
  - `max-width: none`
  - horizontal padding `clamp(4.8rem, 6vw, 12.6rem)`
- The completed changes were deployed to the live Shopify theme.

## Workflow

1. Pull the latest `main` branch before editing.
2. Keep changes scoped to the Rise theme files.
3. Run Shopify Theme Check after edits.
4. Review the storefront before deploying.
5. Push approved changes to live theme ID `153165660354`.
6. Commit and push the same changes to GitHub.

## Shopify CLI environment

Run Shopify CLI from the theme folder with:

```sh
HOME="$PWD/.tmp-shopify-home" \
XDG_CONFIG_HOME="$PWD/.tmp-shopify-config" \
PATH="/Users/main/.cache/codex-runtimes/codex-primary-runtime/dependencies/node/bin:$PATH"
```

The exact Node runtime path may differ on another computer. Use that computer's
Shopify CLI or Node.js installation when necessary.

## Prompt for a new Codex task

Continue development of the MONORAL Shopify site using this repository and
`CODEX_HANDOFF.md`. Pull the latest `main` branch first. Follow new instructions,
edit the theme files, run Shopify Theme Check, preview the storefront, and only
deploy to live theme ID `153165660354` when requested or approved.
