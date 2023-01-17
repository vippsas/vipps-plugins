<!-- START_METADATA
---
title: Vipps Plugins
sidebar_position: 1
pagination_next: null
pagination_prev: null
---
END_METADATA -->

# Vipps Plugins

Vipps provides several open source plugins for various web solutions. This page gives an overview, and the sections below have more details.
We update this table as soon as statuses or plans change.

<!-- START_COMMENT -->

ℹ️ Please use the new documentation:
[Vipps Technical Documentation](https://vippsas.github.io/vipps-developer-docs/docs/vipps-plugins).

## Table of contents

- [API documentation](#api-documentation)
- [Plugins](#plugins)
  - [Craft Commerce](#craft-commerce)
  - [Drupal](#drupal)
  - [Optimizely/EpiServer](#optimizely)
  - [Magento 2](#magento-2)
  - [Magento 1](#magento-1)
  - [Shopify](#shopify)
  - [WooCommerce](#woocommerce)
  - [WordPress](#wordpress)
  - [Wix](#wix)

<!-- END_COMMENT -->

## API documentation

See
[Vipps Developers: Getting started](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/vipps-getting-started)
for documentation about how to integrate with Vipps.


## Plugins

Platform/solution | eCommerce | Vipps Checkout | Recurring  | Login | Support
----------------- | --------- | -------------- |----------- | ----- | -------
Vipps product info | [Vipps på nett](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/) | [Faste betalinger](https://vipps.no/produkter-og-tjenester/bedrift/faste-betalinger/faste-betalinger/) | [Vipps Logg Inn](https://www.vipps.no/produkter-og-tjenester/bedrift/logg-inn-med-vipps/logg-inn-med-vipps/) | - |
WooCommerce | [vipps-woocommerce](https://github.com/vippsas/vipps-woocommerce)  | [vipps-woocommerce](https://github.com/vippsas/vipps-woocommerce)  | [vipps-recurring-woocommerce](https://github.com/vippsas/vipps-recurring-woocommerce) | - | [Details](#woocommerce)
WordPress | - | - | - | [vipps-login-wordpress](https://github.com/vippsas/vipps-login-wordpress) | [Details](#wordpress) |
Magento 2 | [vipps-magento](https://github.com/vippsas/vipps-magento) | [vipps-checkout-magento](https://github.com/vippsas/) | - | [vipps-login-magento](https://github.com/vippsas/vipps-login-magento) | [Details](#magento-2)
Magento 1 | [vipps-magento-v1](https://github.com/vippsas/vipps-magento-v1) | - | - | -| [Details](#magento-1)
Optimizely (Episerver) | [vipps-episerver](https://github.com/vippsas/vipps-episerver) | - | - | [vipps-login-dotnet](https://github.com/vippsas/vipps-login-dotnet) |-
Drupal | [vipps-drupal](https://github.com/vippsas/vipps-drupal) | - | - | [vipps-recurring-drupal](https://github.com/vippsas/vipps-recurring-drupal) | [vipps-login-drupal](https://github.com/vippsas/vipps-login-drupal) |[Details](#drupal)
Shopify | [vipps-shopify](https://github.com/vippsas/vipps-shopify) | - | - | - | [Details](#shopify)
Craft Commerce | To be decided. | - | - | [vipps-craft-login](https://github.com/vippsas/vipps-craft-login)| [Craft-related issues](https://craftcms.com/community) / [Plugin-related issues](https://github.com/elleracompany/vipps-craft-login/issues) / [Vipps-related issues](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/contact)
Wix | [vipps-wix](https://github.com/vippsas/vipps-wix) | - | - | -| [Details](#wix)


### Craft Commerce

![Craft text](images/logo-craft-cms.svg)

* eCommerce: To be decided.
* Recurring: N/A
* Login: [vipps-craft-login](https://github.com/vippsas/vipps-craft-login)

More information about [Craft on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/craft/)

### Drupal

![Drupal logo](images/drupal.png)

* eCommerce: [vipps-drupal](https://github.com/vippsas/vipps-drupal)
* Recurring: [vipps-recurring-drupal](https://github.com/vippsas/vipps-recurring-drupal)
* Login: [vipps-login-drupal](https://github.com/vippsas/vipps-login-drupal)
* Vipps Checkout: Coming soon  

More information about [Drupal on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/drupal/)

### Optimizely

(formerly known as Episerver)

![Episerver logo](images/episerver.png)

* eCommerce: [vipps-episerver](https://github.com/vippsas/vipps-episerver)
* Recurring: N/A  
* Login: [vipps-login-dotnet](https://github.com/vippsas/vipps-login-dotnet)

More information about [Episerver on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/episerver/)

### Magento 2

![Magento logo](images/magento.png)

* eCommerce: [vipps-magento](https://github.com/vippsas/vipps-magento) Support: [submit an issue on GitHub](https://github.com/vippsas/vipps-magento) or [contact us](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/contact).
* Vipps Checkout: [vipps-checkout-magento](https://github.com/vippsas/vipps-checkout-magento) Support: [submit an issue on GitHub](https://github.com/vippsas/vipps-checkout-magento) or [contact us](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/contact).
* Login: [vipps-login-magento](https://github.com/vippsas/vipps-login-magento) Support: [submit an issue on GitHub](https://github.com/vippsas/vipps-login-magento) or [contact us](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/contact).
* Recurring: N/A

More information about [Magento 2 on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/magento/)

### Magento 1

**Important** The Vipps Payment Module for Magento 1 is no longer supported. Vipps will no longer do updates or patches to the module. Run this code at your own risk.

* eCommerce: [vipps-magento-v1](https://github.com/vippsas/vipps-magento-v1)

### Shopify

![Shopify logo](images/shopify.png)

* eCommerce: [vipps-shopify](https://github.com/vippsas/vipps-shopify) Support: [See the support system](https://vipps-shopify.atlassian.net/servicedesk/customer/portal/3)
* Recurring:  N/A
* Login:  N/A

More information about [Shopify on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/shopify/)

**Important deprecation notice!** Shopify has changed their APIs and the previous
Vipps app is no longer supported after July 31 2022. You will have to install a
new Vipps app to be able to support Vipps payments. Remember to capture/refund/cancel
all existing orders before installing the new app. It is also possible to manually
capture/refund/cancel in the [Vipps Portal](https://portal.vipps.no).
The new Vipps payment app is available from [https://apps.shopify.com/vipps?locale=nb](https://apps.shopify.com/vipps?locale=nb).

### WooCommerce

![WooCommerce logo](images/woocommerce.png)

* eCommerce: [vipps-woocommerce](https://github.com/vippsas/vipps-woocommerce)
* Vipps Checkout and Vipps QR codes available through the plugin. Support: [wordpress.org](https://wordpress.org/support/plugin/woo-vipps/)
* Recurring: [vipps-recurring-woocommerce](https://github.com/vippsas/vipps-recurring-woocommerce) Support: [wordpress.org](https://wordpress.org/support/plugin/vipps-recurring-payments-gateway-for-woocommerce/)
* Login: [See WordPress.](#wordpress)

More information about [WooCommerce on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/woocommerce/)

### WordPress

![Wordpress logo](images/wordpress.png)

* eCommerce: [See WooCommerce.](#woocommerce)
* Recurring: [See WooCommerce.](#woocommerce)
* Login: [vipps-login-wordpress](https://github.com/vippsas/vipps-login-wordpress) Support: [wordpress.org](https://wordpress.org/support/plugin/login-with-vipps/)

More information about [Wordpress on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/woocommerce/)

### Wix

![Wix logo](images/wix.png)

* eCommerce: [vipps-wix](https://github.com/vippsas/vipps-wix) Support: [See the support system](https://crude.no/vipps-wix-support/)
* Recurring: N/A
* Login: N/A
