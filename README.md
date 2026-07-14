# Public Shortener Front Page Plugin for YOURLS

Renders a premium, modern, responsive, and Turnstile-secured public URL shortener landing page on your YOURLS home index page.

## Features

- **Premium Front Page**: Replaces the default YOURLS index with a sleek, high-end shortening interface.
- **Cloudflare Turnstile Protection**: Secures the shortening form against bots and spam using Cloudflare Turnstile.
- **Turnstile Key Reuse**: Automatically reuses Turnstile keys from the default Turnstile plugin if installed, or allows custom key configuration in the plugin settings.
- **Color Customization**: Easily adjust the landing page background gradient, text, and accent colors from the settings panel.
- **Responsive Design**: Mobile-first design that looks beautiful on desktops, tablets, and mobile devices.

## Screenshots

<details>
<summary>Screenshot(s)</summary>

| Public Shortener Landing Page | Public Shortener Settings Panel |
| :---: | :---: |
| ![Public Shortener Landing Page](https://i.imgur.com/0pvyW2j.png) | ![Public Shortener Settings Panel](https://i.imgur.com/o6EB2oR.png) |

</details>

## Installation

1. Copy or move the `public-shortener` directory into your YOURLS `user/plugins/` directory.
2. Go to your YOURLS Administration Panel and navigate to **Plugins**.
3. Locate **Public Shortener Front Page** and click **Activate**.

## Settings & Configuration

Navigate to **Public Shortener Settings** in the admin sidebar navigation menu to configure the following settings:

| Setting Option | Type | Default Value | Description |
| :--- | :--- | :--- | :--- |
| `Turnstile Site Key` | String | `""` | Site key for Cloudflare Turnstile CAPTCHA protection. |
| `Turnstile Secret Key` | String | `""` | Secret key for Cloudflare Turnstile CAPTCHA verification. |
| `Page Title` | String | `"Shorten Link"` | Main header title displayed on the public shortening landing page. |
| `Page Subtitle` | String | `"Quickly shorten and optimize your long web URLs"` | Sub-header description text displayed below the title. |
| `Background Gradient Start` | Color | `#0f172a` | Start color (hex) of the background gradient. |
| `Background Gradient End` | Color | `#1e1b4b` | End color (hex) of the background gradient. |
| `Primary Text Color` | Color | `#f8fafc` | Color of the main heading and primary texts. |
| `Secondary Text Color` | Color | `#94a3b8` | Color of sub-headings, labels, and secondary text elements. |
| `Accent Color (Button)` | Color | `#6366f1` | Color of the shorten submit button and other UI highlights. |
| `Accent Hover Color` | Color | `#4f46e5` | Hover state color of the shorten button. |

## Authors

- **Bluscream**
- **Antigravity.AI**

## Other Plugins

Check out our other YOURLS plugins:
- [Manage Protocols](../manage-protocols): Add, view, toggle, and delete allowed URL protocols.
- [Prune Inactive Links](../prune-inactive-links): Automatically deletes old links that receive no clicks.
- [Webhook Notification](../webhook): Sends a JSON POST webhook notification on new link creation.
- [Modern Clicks Log Viewer](../modern-log-viewer): Responsive table of click logs with GeoLite2 geolocation.

## AI Disclaimer

This plugin was created and is maintained with the assistance of Antigravity, an agentic AI coding assistant by Google DeepMind.
