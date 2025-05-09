[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/backdrop-ops/ddev-backdrop-bee/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/backdrop-ops/ddev-backdrop-bee/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/backdrop-ops/ddev-backdrop-bee)](https://github.com/backdrop-ops/ddev-backdrop-bee/commits)
[![release](https://img.shields.io/github/v/release/backdrop-ops/ddev-backdrop-bee)](https://github.com/backdrop-ops/ddev-backdrop-bee/releases/latest)

# DDEV Backdrop Bee

## Overview

Bee is a command line utility for Backdrop CMS. It includes commands that allow developers to interact with Backdrop sites, performing actions like:
- Running cron
- Clearing caches
- Downloading and installing Backdrop
- Downloading, enabling and disabling projects
- Viewing information about a site and/or available projects

See the Release notes and the Changelog for details of changes between versions:
- [Backdrop CMS Bee Project](https://backdropcms.org/project/bee)
- [GitHub Project for Bee](https://github.com/backdrop-contrib/bee)

This add-on integrates Bee into your [DDEV](https://ddev.com/) Backdrop CMS project.

## Installation

To install this add-on, run:

```bash
ddev add-on get backdrop-ops/ddev-backdrop-bee
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Usage

| Command | Description |
| ------- | ----------- |
| `ddev bee` | Run command line utility for Backdrop CMS |

Examples:

```bash
ddev bee
ddev bee status
```

## Credits

**Contributed and maintained by [@jenlampton](https://github.com/jenlampton) and [@wylbur](https://github.com/wylbur)**
