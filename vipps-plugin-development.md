
# Checklist for developing Vipps Plugins

Follow these guidelines while creating plugin modules for Vipps. These are defined to minimize manual support. 

## Table of contents

- [API documentation](#api-documentation)
- [Plugin Checklist](#plugin-checklist)
    - [Documentation](#documentation)
    - [Support](#support)
    - [Development and required features](#development-and-required-features)
- [Questions?](#questions)


## API documentation

See: [Getting started](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/vipps-getting-started).


## Plugin Checklist

Use this info as a guideline to make sure documentation and the required features are followed. These requirements are in addition to the features described in [our default checklists](https://vippsas.github.io/vipps-developer-docs/docs/vipps-partner#finishing-the-integration-and-going-live).

The following sections must be added to the plugin/module description.

### Documentation

Documentation must include the following information.

| Required content | Comment |
|-----|-----------|
|     List of features| A list of available features and information about how to configure, enable, and disable them. |
|     Install plugin| Add a description of how to install the module. |
|     Prerequisites| Provide a list of prerequisites for using the module.|
|     Configuration| Add information about all the configurable features. |
|     Get API keys| Include a detailed 1-2-3-type list with reference how to [get API keys](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/common-topics/api-keys#getting-the-api-keys). |
|     Info about on-site-messaging| Specify how to configure in module or add a link to [Vipps on-site-messaging](https://vippsas.github.io/vipps-developer-docs/docs/APIs/checkout-api/vipps-checkout-on-site-messaging). |
|     Notification on available updates| If it's not default by platform, show a notification banner when an update is available for the module. |
|     API Dashboard| Inform that merchants can use the [Vipps API Dashboard](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/vipps-resources#api-dashboard) to follow up on errors.|
|     Release notes| Add detailed release notes for new releases. Do not add cryptic comments about updates, but describe what is new. |
|     Add FAQ| Add a list of frequently asked questions and information about other typical issues related to the platform and module.|


### Support 

Add a separate section for support.

| Required content | Comment |
|-----|-----------|
|     Support| Provide information about how to get help with the plugin or module. Link to the plugin's support system. Do not link to Vipps contact page. |
|     Link to Vipps Portal| Inform the merchant that they can manage their sale units on the Vipps portal. For example: "You can manage your sale unit (e.g., change name and logo), see reports of all payments, etc. on [portal.vipps.no](https://portal.vipps.no)."|
|     Link to Vipps FAQ| Provide a link to the Vipps FAQs. For example: "For typical questions and answers about Vipps payments and APIs, see the [Vipps FAQs](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/faqs)."|
|     Info about contributing on GitHub| Add to the _issues_ tab on the GitHub repo. |
|     Link to Vipps "help"-pages| "[The Vipps help page](https://vipps.no/hjelp/vipps/)"|
|     Link to Vipps customer center for merchants| "If you need help with your customer relationship with Vipps, [Contact Vipps customer service](https://vipps.no/hjelp/vipps/)."|
|     Link to newsletters| "Vipps has a [technical newsletter](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/newsletters) with news about APIs, etc. We recommend subscribing to it." |


### Development and required features

Include the following details and routines as part of the module. 

| Required content | Comment |
|-----|-----------|
|     Error Logging| Include the option to activate debugging mode with enhanced logging and tracking of all Vipps calls and responses. Track both [error codes and error messages](https://vippsas.github.io/vipps-developer-docs/docs/APIs/ecom-api/vipps-ecom-api#error-codes). Present the results in a separate page of the module configuration, with the complete Vipps error message displayed.
|     Error Handling| Ensure that users, both administrators and customers, receive an unambiguous notification when anything goes wrong. For POS integration, present the information to both the cashier and the customers.
|     Follow up on GitHub security/Dependabot alerts | Ensure that security alerts are added to pull requests and that there is a monthly routine in place for handling these. |
|     On-site-messaging configuration| Add a configurable _On-site-messaging_ feature to ease the [Vipps on-site-messaging](https://vippsas.github.io/vipps-developer-docs/docs/APIs/checkout-api/vipps-checkout-on-site-messaging). |        



## Questions?

We're always happy to help with code or other questions you might have!
Please create an GitHub issue or pull request in the related repos or [contact us](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/contact) for general Vipps API related questions.

Sign up for our [Technical newsletter for developers](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/newsletters/).







