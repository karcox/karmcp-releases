# KarMCP — releases

This repository is the distribution channel for **KarMCP**, a WordPress plugin that exposes a site as MCP tools so an AI agent can build Elementor pages, manage content and audit the site.

It holds no source code. Every version is published here as a [release](../../releases) with an installable `karmcp-<version>.zip` attached.

## Installing

1. Download `karmcp-<version>.zip` from the [latest release](../../releases/latest).
2. In WordPress, go to **Plugins → Add New → Upload Plugin**, choose the zip and activate it.

## Updates

Installed copies check this repository's latest release and offer new versions on the **Plugins** screen, where they install with the usual *Update now* button. The answer is cached for six hours; the **Check for updates** link on the plugin's row asks again immediately.

The check accepts only a published release whose tag reads as a newer version and whose download is a `.zip` served by GitHub. It can be switched off with the `KARMCP_NO_UPDATE_CHECK` constant or the `karmcp_update_check_enabled` filter.

## Licence

GPL-2.0-or-later. The licence and copyright notices travel inside every zip.
