<!-- START_METADATA
---
title: Introduction to Vipps Plugins
sidebar_label: Introduction
sidebar_position: 1
hide_table_of_contents: true
pagination_next: null
pagination_prev: null
---
END_METADATA -->


import ApiSchema from '@theme/ApiSchema';
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# Plugins

<!-- START_COMMENT -->

ℹ️ Please use the website:
[Vipps MobilePay Technical Documentation](https://developer.vippsmobilepay.com/docs/plugins).

<!-- END_COMMENT -->

Vipps provides several open source plugins for various web solutions. This page gives an overview, and the sections below have more details.
We update this table as soon as statuses or plans change.

If you need help with your customer relationship with Vipps, [contact customer service](https://vipps.no/hjelp/vipps/).

## Plugin platforms

The following plugin platforms can be used with
[Payment *(Vipps på nett)*](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/),
[Checkout](https://www.vipps.no/produkter-og-tjenester/bedrift/bestill-vipps-checkout/checkout/),
[Recurring *(Faste betalinger)*](https://vipps.no/produkter-og-tjenester/bedrift/faste-betalinger/faste-betalinger/), and
[Login](https://www.vipps.no/produkter-og-tjenester/bedrift/logg-inn-med-vipps/logg-inn-med-vipps/).


| Platform                      | Payment | Checkout | Recurring  | Login |
| ----------------------------- | ------- | -------- |----------- | ----- |
| [Drupal](drupal.md)           |   ✅   |          |    ✅     |   ✅  |
| [Magento](magento.md)         |   ✅   |    ✅    |           |   ✅  |
| [Optimizely](optimizely.md)   |   ✅   |          |           |   ✅  |
| [Shopify](shopify.md)         |   ✅   |    ✅    |           |       |
| [Wix](wix.md)                 |   ✅   |          |           |       |
| [WooCommerce](woocommerce.md) |   ✅   |    ✅    |    ✅     |   ✅  |
| [WordPress](wordpress.md)     |        |           |           |   ✅  |


### Features

<Tabs
defaultValue="Payment"
groupId="sdk-choice"
values={[
{label: 'Payment', value: 'Payment'},
{label: 'Checkout', value: 'Checkout'},
{label: 'Recurring', value: 'Recurring'},
{label: 'Login', value: 'Login'},
]}>

<TabItem value="Payment">

| Platform                   | Pay with Vipps | Express Checkout | Receipts | Branding | QR codes |
| -------------------------- | -------------- | ---------------- |----------| ---------|----------|
| [Drupal][drupal]           |       ✅      |                  |           |          |           |
| [Magento][magento]         |       ✅      |        ✅        |    ✅   |           |           |
| [Optimizely][episerver]    |       ✅      |        ✅        |          |          |           |
| [Shopify][shopify]         |       ✅      |         ✅       |          |          |           |
| [Wix][wix]                 |       ✅      |                  |          |           |           |
| [WooCommerce][woocommerce] |       ✅      |        ✅        |    ✅   |     ✅   |     ✅   |

Relevant links:

* [Express checkout](https://developer.vippsmobilepay.com/docs/APIs/ecom-api/vipps-ecom-api/#express-checkout-payments)
* [Receipts](https://developer.vippsmobilepay.com/docs/APIs/checkout-api/vipps-checkout-api/#receipts)

</TabItem>

<TabItem value="Checkout">

| Platform                      | Pay with Vipps | Pay with Card |  Branding | Express Checkout | Receipts | QR codes |
| ----------------------------- | -------------- | ------------- | --------- | ---------------- |----------|----------|
| [Magento][checkout-magento]   |       ✅      |      ✅       |           |                  |    ✅   |           |
| [Shopify][checkout-shopify]   |       ✅      |      ✅       |    ✅    |                  |    ✅   |           |
| [WooCommerce][woocommerce]    |       ✅      |      ✅       |    ✅    |        ✅        |    ✅   |     ✅   |

Relevant links:

* [How Checkout works for WooCommerce](https://developer.vippsmobilepay.com/docs/APIs/checkout-api/vipps-checkout-how-it-works-woocommerce/)
* [Express checkout](https://developer.vippsmobilepay.com/docs/APIs/ecom-api/vipps-ecom-api/#express-checkout-payments)
* [Receipts](https://developer.vippsmobilepay.com/docs/APIs/checkout-api/vipps-checkout-api/#receipts)

</TabItem>

<TabItem value="Recurring">

| Platform                             | Price campaign | Period campaign |
| ------------------------------------ | -------------- | --------------- |
| [Drupal][recurring-drupal]           |       ✅      |                 |
| [WooCommerce][recurring-woocommerce] |       ✅      |       ✅        |

Relevant links:

* [Campaign types](https://developer.vippsmobilepay.com/docs/APIs/recurring-api/vipps-recurring-api/#campaigns)

</TabItem>
<TabItem value="Login">

| Platform                                   | Sign up | Log in | User info | Link account |
| ------------------------------------------ | ------- | ------ |---------- | ------------ |
| [Drupal][login-drupal]                     |         |   ✅  |           |              |
| [Magento][login-magento]                   |    ✅   |  ✅   |          |    ✅        |
| [Optimizely][login-dotnet]                 |    ✅   |   ✅  |    ✅    |              |
| [WooCommerce / WordPress][login-wordpress] |    ✅   |   ✅  |    ✅    |     ✅      |


</TabItem>
</Tabs>



## Plugin development

If you are interested in creating a plugin, see [Plugin development](plugin-development.md).


[checkout-magento]: /docs/plugins-ext/checkout-magento/
[checkout-shopify]: /docs/plugins-ext/checkout-shopify/
[drupal]: /docs/plugins-ext/drupal/
[episerver]: /docs/plugins-ext/episerver/
[login-dotnet]: /docs/plugins-ext/login-dotnet/
[login-drupal]: /docs/plugins-ext/login-drupal/
[login-magento]: /docs/plugins-ext/login-magento/
[login-wordpress]: /docs/plugins-ext/login-wordpress/
[magento]: /docs/plugins-ext/magento/
[recurring-drupal]: /docs/plugins-ext/recurring-drupal/
[recurring-woocommerce]: /docs/plugins-ext/recurring-woocommerce/
[shopify]: /docs/plugins-ext/shopify/
[wix]: /docs/plugins-ext/wix/
[woocommerce]: /docs/plugins-ext/woocommerce/
