# WDOD Project Overview

Custom WordPress theme and plugins built for this project. Each piece lives in its own repository and is versioned independently.

## Repositories

| Repository | What it is |
|---|---|
| [wdod-starter](https://github.com/datsenkoolena/wdod-starter) | Classic WordPress starter theme — Elementor, WooCommerce, ACF and WPML ready. |
| [wdod-site-toolkit](https://github.com/datsenkoolena/wdod-site-toolkit) | Maintenance/troubleshooting toolkit: environment report, debug log viewer, staging mode, performance tweaks, login hardening, WP-CLI commands. |
| [wdod-elementor-widgets](https://github.com/datsenkoolena/wdod-elementor-widgets) | Elementor widgets: Pricing Table, Team Member, Testimonial Slider (with shortcode fallbacks). |
| [wdod-woo-connector](https://github.com/datsenkoolena/wdod-woo-connector) | Pushes WooCommerce orders to an external API via signed webhooks with background retries. |

## Local setup

All four are developed together against a single Local (Local WP) site, with the theme and plugins linked into `wp-content/themes` and `wp-content/plugins` respectively.
