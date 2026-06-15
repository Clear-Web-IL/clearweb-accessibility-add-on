# Clearweb Accessibility Add-on

WordPress accessibility widget with full Hebrew (עברית) and RTL support — built for Israeli businesses.

Published by [Clear Web](https://clearweb.co.il) as open source under GPLv2 or later.

## Features

- Visitor-facing accessibility toolbar (typography, vision, reading aids, navigation)
- Quick-start presets (low vision, ADHD-friendly, reduce motion, high contrast)
- Accessibility problem reporting via email
- Admin settings for widget position and vertical offset
- Hebrew (`he_IL`) translations and RTL layout

## Requirements

- WordPress 6.4+
- PHP 8.1+
- Node.js 18+ (development only, for building JavaScript bundles)

## Installation

1. Download or clone this repository into `wp-content/plugins/clearweb-accessibility-add-on/`
2. Run `npm install && npm run build` to generate the bundled assets in `build/`
3. Activate **Clearweb Accessibility Add-on** in WordPress Admin

For a production-ready ZIP without Node.js on the server, run `npm run zip` locally (Windows) or `npm run zip:linux` (macOS/Linux) and upload the generated archive.

Pre-built ZIPs for each version are also available on [GitHub Releases](https://github.com/Clear-Web-IL/clearweb-accessibility-add-on/releases).

## Development

```bash
npm install
npm run build    # compile assets/src → build/
npm run start    # watch mode
npm run zip      # create WordPress release ZIP
```

Source files live in `assets/src/`. Bundled output is written to `build/`.

## WordPress.org

This plugin is submitted to the [WordPress Plugin Directory](https://wordpress.org/plugins/) as **clearweb-accessibility-add-on**.

## License

GPLv2 or later. See [license.txt](license.txt).

OpenDyslexic font files are bundled under SIL Open Font License 1.1 — see [assets/fonts/opendyslexic/OFL.txt](assets/fonts/opendyslexic/OFL.txt).

## Links

- Website: [clearweb.co.il](https://clearweb.co.il)
- Organization: [Clear-Web-IL on GitHub](https://github.com/Clear-Web-IL)
