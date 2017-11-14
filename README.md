# Magento 2 Module - B2B

![https://www.augustash.com](http://augustash.s3.amazonaws.com/logos/ash-inline-color-500.png)

**This is a private module and is not currently aimed at public consumption.**

## Overview

The `Augustash_B2b` module is our base module for B2B functionality. It must be present on all B2B installations.

This module provides several B2B branding elements. For example, it adds a link to B2B customer support in Admin, and it displays "B2B Edition" at the bottom of the site. Also, the module adds the configuration page for B2B settings where an admin user can enable or disable a B2B feature. Disabling a B2B feature in store configurations disables this feature for the storefront only, and it is still available in the admin panel.

## Installation

This module must be installed to use and to configure the other B2B modules. It can be uninstalled after all other B2B modules are uninstalled.

```bash
composer config repositories.augustash composer https://packages.augustash.com/repo/private
composer require augustash/module-b2b:1.0.0
```

## Structure

[Typical file structure for a Magento 2 module](http://devdocs.magento.com/guides/v2.2/extension-dev-guide/build/module-file-structure.html).
