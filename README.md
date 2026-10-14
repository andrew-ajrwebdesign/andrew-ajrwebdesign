# Andrew — AJR Web Design

WordPress developer based in Freiburg, Germany. I build fast, client-editable WordPress sites as a full-site-editing block theme plus a settings-driven core plugin, and I look after SEO, performance and Google Ads for the sites I run on retainer.

🌐 [ajrwebdesign.com](https://ajrwebdesign.com)

## The starter kit

Every site I build starts from these two repositories:

- **[ajr-starter-theme](https://github.com/andrew-ajrwebdesign/ajr-starter-theme)**: an FSE block theme. `theme.json` is the design system, every section is a real core block, and the client can edit all of it in the Site Editor.
- **[ajr-starter-core](https://github.com/andrew-ajrwebdesign/ajr-starter-core)**: the core plugin. It holds business details and schema, Google tags with Consent Mode, the redirect map, image sizes and AI-agent access, and everything it does is a setting. A CI check fails the build if anything is hardcoded.

[![Try the starter kit in WordPress Playground](https://img.shields.io/badge/Try%20it-WordPress%20Playground-3858e9?logo=wordpress)](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/andrew-ajrwebdesign/ajr-starter-theme/main/blueprint.json)

## How I work

- **Client-editable first.** No shortcodes, no page-builder lock-in, no HTML blobs.
- **Nothing hardcoded.** If a value is on the site, it has an admin field.
- **Measured, not guessed.** Lighthouse 90+ is the floor, and every performance claim in the code comments comes from a real before/after audit.
- **Gated.** WordPress Coding Standards, PHPStan, unit tests and a pre-deploy gate run before anything ships.
