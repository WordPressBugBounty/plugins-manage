=== Manage ===

Contributors: elemntor
Tags: elementor, manage, websites, admin, monitoring, performance, updates
Requires at least: 6.6
Tested up to: 6.9
Stable tag: 1.0.2
Requires PHP: 7.4
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Manage multiple WordPress websites from one place using your Elementor account. Safe updates, monitoring, and bulk actions powered by Elementor.

## Description

**Manage** is your control panel for keeping multiple WordPress sites up to date from a single place.
It brings together monitoring, safe updates, and management features directly into the Elementor ecosystem.

### Key Features

- Bulk plugin, theme, and core updates with Safe Updates
- Database cleanup across sites
- Performance and page speed monitoring
- One-click login to any managed site
- Per-site activity logs

Manage helps agencies, freelancers, and site owners save time and reduce risk when working with multiple sites.

## Installation

1. Upload the plugin file or install it directly through the **WordPress Plugins** screen.
2. Activate the plugin through the **Plugins** screen in WordPress.
3. Click **“Connect to Start”** or navigate to **Elementor → Site Management** in your dashboard to connect.

## Frequently Asked Questions

### Do I need Elementor Pro?
No. Manage works with your WordPress installation—no need for any other Elementor plugin.

### Can I manage non-Elementor sites?
Yes. Any WordPress site can be connected through Manage. Bulk operations require an Elementor One subscription.

### Is Manage free?
Yes. The free version includes unlimited connected sites with view-only monitoring.
Site connections are unlimited, even on the free plan.

== External Services ==
This plugin connects to an external APIs from Elementor https://my.elementor.com/manage/api/ to enable centralized website management and remote actions within Manage when used with an Elementor account. It facilitates synchronization between the user's site and Elementor's infrastructure services to ensure accurate site insights, update and database management.
Elementor's terms and conditions: https://elementor.com/terms/
Privacy Policy: https://elementor.com/about/privacy/
Full details regarding Manage remote feature can be found on: https://elementor.com/products/manage/ and the Elementor Help Center at https://elementor.com/help/

**Data Sent:**
The plugin sends limited technical information from your site to Elementor so it can appear in your dashboard and be managed remotely. This includes:
- Site metadata: URL, WordPress and PHP versions, plugin and theme names with their versions.
- Health and status info: update and activation availability, and results of safe updates or rollbacks. Performance is measured independently from this plugin using Google PageSpeed.
- Connection details: a unique site ID and secure authentication token tied to your Elementor account. List of users are shared with Elementor to enable one-click access to the site.
**Data Received:**
From Elementor's side, your site receives data and instructions needed for management actions. This includes:
- Update and rollback commands for plugins, themes and core.
- Configuration data to sync your site with the dashboard.
All communication is encrypted and verified through signed tokens to ensure only authorized actions are performed.

## Screenshots

1. Main dashboard with site overview
2. Bulk update panel for plugins and themes
3. Monitoring tab with uptime and performance info

## Changelog

### 1.0.2
- Improved support for installing plugins from ZIP files.

### 1.0.1
- Handle license state before displaying the option to connect.

### 1.0.0
- Initial release

## Support

For support and documentation, visit [https://elementor.com](https://elementor.com).
