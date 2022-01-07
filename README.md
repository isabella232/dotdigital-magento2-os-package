# Dotdigital package for Magento Open Source
[![Packagist Version](https://img.shields.io/packagist/v/dotdigital/dotdigital-magento2-os-package?color=green&label=latest)](https://github.com/dotmailer/dotdigital-magento2-os-package/releases)

## Contents
This is a Composer metapackage containing the following modules:
- Dotdigitalgroup_Email
- Dotdigitalgroup_Chat
- Dotdigitalgroup_Sms
- Dotdigitalgroup_EmailGraphQl
- Dotdigitalgroup_ChatGraphQl

## Installation
**Steps:**
1. You must ‘purchase’ the relevant package via our vendor page on the [Magento Marketplace](https://marketplace.magento.com/partner/dotdigitalLtd).
2. Any existing `require` instructions in your composer.json relating to `dotmailer/*` packages must be removed.
3. Now, require the correct package.
```
composer require dotdigital/dotdigital-magento2-os-package --no-update
composer update
```
