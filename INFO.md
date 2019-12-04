# Aqua Fiesta Theme

[![Build Status](https://www.travis-ci.org/PurelyNicole/aqua-fiesta-theme.svg?branch=master)](https://www.travis-ci.org/PurelyNicole/aqua-fiesta-theme)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)


> Aqua Fiesta Theme by Nicole Zeckner

An aqua theme with orange accents, designed to match the accent wall in my kitchen. The theme name comes from that paint color.

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/PurelyNicole/aqua-fiesta-theme/master/docs/theme-overview.png)

![Theme - Kitchen Dash](https://raw.githubusercontent.com/PurelyNicole/aqua-fiesta-theme/master/docs/kitchen-dash.PNG)

### Map

![Theme - Map](https://raw.githubusercontent.com/PurelyNicole/aqua-fiesta-theme/master/docs/theme-map.png)

### Logbook

![Theme - Logbook](https://raw.githubusercontent.com/PurelyNicole/aqua-fiesta-theme/master/docs/theme-logbook.png)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/PurelyNicole/aqua-fiesta-theme/master/docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/PurelyNicole/aqua-fiesta-theme/master/docs/theme-configuration.png)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/PurelyNicole/aqua-fiesta-theme/master/docs/theme-profile.png)

## Installation

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Go to the Community Store.
3. Search for `Template`.
4. Navigate to `Template` theme.
5. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.
