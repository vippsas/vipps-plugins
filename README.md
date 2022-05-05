# Vipps Plugins

Vipps provides several open source plugins for various web solutions. This page gives an overview, and the sections below have more details.
We update this table as soon as statuses or plans change.

## Table of contents

- [Vipps Plugins](#vipps-plugins)
  - [Table of contents](#table-of-contents)
  - [API documentation](#api-documentation)
  - [Plugins](#plugins)
    - [Craft Commerce](#craft-commerce)
    - [Drupal](#drupal)
    - [Optimizely/EpiServer](#episerver)
    - [Magento 2](#magento-2)
    - [Magento 1](#magento-1)
    - [Shopify](#shopify)
    - [WooCommerce](#woocommerce)
    - [WordPress](#wordpress)
    - [BigCommerce](#bigcommerce)
    - [Wix](#wix)
  - [Additional developer resources](#additional-developer-resources)
  - [Questions?](#questions)

## API documentation

See: [Getting started](https://github.com/vippsas/vipps-developers/blob/master/vipps-getting-started.md#getting-started).

## Plugins


Platform/solution | eCommerce | Recurring  | Login | Support
----------------- | --------- | ---------- | ----- | -------
Vipps product info | [Vipps på nett](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/) | [Faste betalinger](https://vipps.no/produkter-og-tjenester/bedrift/faste-betalinger/faste-betalinger/) | [Vipps Logg Inn](https://www.vipps.no/produkter-og-tjenester/bedrift/logg-inn-med-vipps/logg-inn-med-vipps/) | - |
WooCommerce | [vipps-woocommerce](https://github.com/vippsas/vipps-woocommerce) | [vipps-recurring-woocommerce](https://github.com/vippsas/vipps-recurring-woocommerce) | - | [Details](#woocommerce)
WordPress | - | - | [vipps-login-wordpress](https://github.com/vippsas/vipps-login-wordpress) | [Details](#wordpress) |
Magento 2 | [vipps-magento](https://github.com/vippsas/vipps-magento) | - | [vipps-login-magento](https://github.com/vippsas/vipps-login-magento) | [Details](#magento-2)
Magento 1 | [vipps-magento-v1](https://github.com/vippsas/vipps-magento-v1) | - | -| [Details](#magento-1)
Optimizelt/Episerver | [vipps-episerver](https://github.com/vippsas/vipps-episerver) | - | [vipps-login-dotnet](https://github.com/vippsas/vipps-login-dotnet) |-
Drupal | [vipps-drupal](https://github.com/vippsas/vipps-drupal) | [vipps-recurring-drupal](https://github.com/vippsas/vipps-recurring-drupal) | [vipps-login-drupal](https://github.com/vippsas/vipps-login-drupal) |[Details](#drupal)
Shopify | [vipps-shopify](https://github.com/vippsas/vipps-shopify) | - | - | [Details](#shopify)
Craft Commerce | To be decided. | - | [vipps-craft-login](https://github.com/vippsas/vipps-craft-login)| [Craft-related issues](https://craftcms.com/community) / [Plugin-related issues](https://github.com/elleracompany/vipps-craft-login/issues) / [Vipps-related issues](https://github.com/vippsas/vipps-developers/blob/master/contact.md) 
Wix | [vipps-wix](https://github.com/vippsas/vipps-wix) | - | -| [Details](#wix)
BigCommerce | To be decided. | - | -|-

### Craft Commerce

![Craft text][craft-cms-logo]  

**eCommerce**: To be decided.  
**Recurring**: N/A  
**Login**: [vipps-craft-login](https://github.com/vippsas/vipps-craft-login)  

More information about [Craft on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/craft/)

### Drupal  

![Drupal logo][drupal-logo]  

**eCommerce**: [vipps-drupal](https://github.com/vippsas/vipps-drupal)  
**Recurring**: [vipps-recurring-drupal](https://github.com/vippsas/vipps-recurring-drupal)  
**Login**: [vipps-login-drupal](https://github.com/vippsas/vipps-login-drupal)  

More information about [Drupal on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/drupal/)

### Optimizely (formerly known as Episerver)  

![Episerver logo][episerver-logo]  

**eCommerce**: [vipps-episerver](https://github.com/vippsas/vipps-episerver)  
**Recurring**: N/A  
**Login**: [vipps-login-dotnet](https://github.com/vippsas/vipps-login-dotnet)  

More information about [Episerver on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/episerver/)

 

### Magento 2

![Magento logo][magento-logo] 

**eCommerce**: [vipps-magento](https://github.com/vippsas/vipps-magento) **Support:** [submit an issue on GitHub](https://github.com/vippsas/vipps-magento) or send a mail to integration@vipps.no 

**Login**: [vipps-login-magento](https://github.com/vippsas/vipps-login-magento) **Support:** [submit an issue on GitHub](https://github.com/vippsas/vipps-login-magento) or mail to integration@vipps.no 

**Recurring**: N/A  

More information about [Magento 2 on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/magento/)

### Magento 1

**Important** The Vipps Payment Module for Magento 1 is no longer supported. Vipps will no longer do updates or patches to the module. Run this code at your own risk. 

**eCommerce**: [vipps-magento-v1](https://github.com/vippsas/vipps-magento-v1) 


### Shopify  

![Shopify logo][shopify-logo]  

**eCommerce**: [vipps-shopify](https://github.com/vippsas/vipps-shopify) **Support:** [See the support system](https://vipps-shopify.atlassian.net/servicedesk/customer/portal/3)  
**Recurring**:  N/A  
**Login**:  N/A

More information about [Shopify on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/shopify/)


### WooCommerce

![WooCommerce logo][woocommerce-logo]  

**eCommerce**: [vipps-woocommerce](https://github.com/vippsas/vipps-woocommerce) **Support:** [wordpress.org](https://wordpress.org/support/plugin/woo-vipps/)  
**Recurring**: [vipps-recurring-woocommerce](https://github.com/vippsas/vipps-recurring-woocommerce) **Support:** [wordpress.org](https://wordpress.org/support/plugin/vipps-recurring-payments-gateway-for-woocommerce/)  
**Login**: [See WordPress.](#wordpress)  

More information about [WooCommerce on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/woocommerce/)

### WordPress

![Wordpress logo][wordpress-logo]  

**eCommerce**: [See WooCommerce.](#woocommerce)  
**Recurring**: [See WooCommerce.](#woocommerce)  
**Login**: [vipps-login-wordpress](https://github.com/vippsas/vipps-login-wordpress) **Support:** [wordpress.org](https://wordpress.org/support/plugin/login-with-vipps/) 

More information about [Wordpress on vipps.no](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/woocommerce/)


### BigCommerce  
![BigCommerce logo][bigcommerce-logo]  

**eCommerce**: To be decided.  
**Recurring**: N/A  
**Login**: N/A  

### Wix  

![Wix logo][wix-logo]  
**eCommerce**: [vipps-wix](https://github.com/vippsas/vipps-wix) **Support:** [See the support system](https://crude.no/vipps-wix-support/)  
**Recurring**: N/A  
**Login**: N/A  

[bigcommerce-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/bigcommerce.png "BigCommerce logo"
[craft-cms-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/logo-craft-cms.svg "Craft cms logo"
[drupal-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/drupal.png "Craft cms logo"
[episerver-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/episerver.png "EpiServer logo"
[magento-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/magento.png "Magento logo"
[shopify-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/shopify.png "Shopify logo"
[wix-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/wix.png "Wix logo"
[wordpress-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/wordpress.png "Wordpress logo"
[woocommerce-logo]: https://github.com/vippsas/vipps-developers/blob/master/images/logos/woocommerce.png "WooCommerce logo"



## Additional developer resources

* Developer overview: https://vipps.no/developer
* Products, personal: http://vipps.no/privat
* Products, business: http://vipps.no/bedrift

## Questions?

We're always happy to help with code or other questions you might have!
Please create an GitHub issue or pull request in the related repos or [contact Vipps Integration](https://github.com/vippsas/vipps-developers/blob/master/contact.md) for general Vipps API related questions.

Sign up for our [Technical newsletter for developers](https://github.com/vippsas/vipps-developers/tree/master/newsletters).
