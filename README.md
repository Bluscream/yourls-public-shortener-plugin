# yourls-public-shortener-plugin

Renders a premium, modern, and Turnstile-secured public URL shortener landing page on your YOURLS home page.

## Features

- **Premium Front Page**: Replaces the default YOURLS index with a sleek, user-friendly shortening interface.
- **Cloudflare Turnstile Protection**: Secures the shortening form against bots and spam using Cloudflare Turnstile.
- **Turnstile Key Reuse**: Automatically reuses Turnstile keys from the default Turnstile plugin if installed, or allows custom key configuration in the plugin file.
- **Responsive Design**: Looks great on desktops, tablets, and mobile devices.

## Installation

1. Copy or move the `public-shortener` directory into your YOURLS `user/plugins/` directory.
2. Go to your YOURLS Administration Panel and navigate to **Plugins**.
3. Locate **Public Shortener Front Page** and click **Activate**.

## Usage

After activation, navigate to your YOURLS base URL (the index page) to view the newly rendered public shortener landing page.

## Authors

- **Bluscream**
- **Antigravity.AI**

## Other Plugins

Check out our other YOURLS plugins:
- [Manage Protocols](../manage-protocols): Add, view, toggle, and delete allowed URL protocols.
- [Prune Inactive Links](../prune-inactive-links): Automatically deletes old links that receive no clicks.
- [Modern Clicks Log Viewer](../modern-log-viewer): Responsive table of click logs with GeoLite2 geolocation.
