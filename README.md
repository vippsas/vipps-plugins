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
[Vipps MobilePay Technical Documentation](https://developer.vippsmobilepay.com/docs/vipps-plugins).

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
| [Craft Commerce](craft.md)    |        |          |           |   ✅  |
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
</TabItem>

<TabItem value="Checkout">

| Platform                      | Pay with Vipps | Pay with Card |  Branding | Express Checkout | Receipts | QR codes |
| ----------------------------- | -------------- | ------------- | -------- | ---------------- |----------|----------|
| [Magento][checkout-magento]   |       ✅      |      ✅       |          |                  |     ✅   |           |
| [Shopify][checkout-shopify]   |       ✅      |      ✅       |    ✅    |                  |    ✅   |           |
| [WooCommerce][woocommerce]    |        ✅     |      ✅       |    ✅    |        ✅        |    ✅   |     ✅   |
</TabItem>

<TabItem value="Recurring">

| Platform                             | Create agreements | Manage agreements | Campaign types |
| ------------------------------------ | ----------------- | ----------------- | -------------- |
| [Drupal][recurring-drupal]           |     ✅           |         ✅        |                |
| [WooCommerce][recurring-woocommerce] |     ✅           |         ✅        |                |

</TabItem>
<TabItem value="Login">

| Platform                                   | Sign up | Log in | User info | Link account |
| ------------------------------------------ | ------- | ------ |---------- | ------------ |
| [Craft Commerce][craft-login]              |    ✅   |  ✅   |    ✅    |    ✅       |
| [Drupal][login-drupal]                     |         |   ✅  |           |              |
| [Magento][login-magento]                   |    ✅   |  ✅   |          |    ✅        |
| [Optimizely][login-dotnet]                 |    ✅   |   ✅  |    ✅    |              |
| [WooCommerce / WordPress][login-wordpress] |    ✅  |   ✅  |    ✅    |     ✅      |


</TabItem>
</Tabs>



## Plugin development

If you are interested in creating a plugin, see [Plugin development](plugin-development.md).


[checkout-magento]: https://developer.vippsmobilepay.com/docs/plugins-ext/checkout-magento/
[checkout-shopify]: https://developer.vippsmobilepay.com/docs/plugins-ext/checkout-shopify/
[craft-login]: https://developer.vippsmobilepay.com/docs/plugins-ext/craft-login/
[drupal]: https://developer.vippsmobilepay.com/docs/plugins-ext/drupal/
[episerver]: https://developer.vippsmobilepay.com/docs/plugins-ext/episerver/
[login-dotnet]: https://developer.vippsmobilepay.com/docs/plugins-ext/login-dotnet/
[login-drupal]: https://developer.vippsmobilepay.com/docs/plugins-ext/login-drupal/
[login-magento]: https://developer.vippsmobilepay.com/docs/plugins-ext/login-magento/
[login-wordpress]: https://developer.vippsmobilepay.com/docs/plugins-ext/login-wordpress/
[magento]: https://developer.vippsmobilepay.com/docs/plugins-ext/magento/
[recurring-drupal]: https://developer.vippsmobilepay.com/docs/plugins-ext/recurring-drupal/
[recurring-woocommerce]: https://developer.vippsmobilepay.com/docs/plugins-ext/recurring-woocommerce/
[shopify]: https://developer.vippsmobilepay.com/docs/plugins-ext/shopify/
[wix]: https://developer.vippsmobilepay.com/docs/plugins-ext/wix/
[woocommerce]: https://developer.vippsmobilepay.com/docs/plugins-ext/woocommerce/
