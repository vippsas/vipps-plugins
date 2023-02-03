
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
|     List of features| A list of available features and info how to configure, enable/disable them. |
|     Install plugin| How to install the module|
|     Prerequisites| What are prerequisites for using the module|
|     Configuration| Add info about all configurable features|
|     Get API keys| Include a detailed 1-2-3-type list with reference how to [get API keys](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/common-topics/api-keys#getting-the-api-keys)|
|     Info about on-site-messaging| How to configure in module or add link to [Vipps on-site-messaging](https://vippsas.github.io/vipps-developer-docs/docs/APIs/checkout-api/vipps-checkout-on-site-messaging)|
|     Notification on available updates| If not default by platform, add a notification banner if an available update for module is added. |
|     API Dashboard| Add info that merchants can use Vipps' [API Dashboard](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/vipps-resources#api-dashboard) to follow up on errors|
|     Release notes| Add detailed release notes for new releases. Do not add cryptic comments about updates. Describe what's new|
|     Add FAQ| Add a list of frequently asked questions and other typical issues related to the platform and module|


### Support 

Add seperate section for support.

| Required content | Comment |
|-----|-----------|
|     Support| How to get help. Link to the plugins's support system (do not link to [Vipps contact page](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/contact))|
|     Link to Vipps Portal| Inform merchant that they can manage their sale units, see reports, etc: "On [portal.vipps.no](https://portal.vipps.no) you can manage your sale unit (change name and logo, etc), see reports of all payments, etc"|
|     Link to Vipps FAQ| "For typical questions and [answers about Vipps payments and APIs](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/faqs)"|
|     Info about contributing on GitHub| Add to issues tab on the GitHub repo|
|     Link to Vipps "help"-pages| "[The Vipps help page](https://vipps.no/hjelp/vipps/)"|
|     Link to Vipps Kundesenter for merchants| "If you need help with your customer relationship with Vipps: [Contact Vipps customer service](https://vipps.no/hjelp/vipps/)"|
|     Link to newsletters| "Vipps has a [technical newsletter](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/newsletters) with news about APIs, etc. We recommend subscribing to it"|


### Development and required features

Following details and routines must be part of the module developed. 

| Required content | Comment |
|-----|-----------|
|     Error Logging| Option to activate debugging mode with enhanced logging, and track all Vipps calls and responses. Track both [error code and error message](https://vippsas.github.io/vipps-developer-docs/docs/APIs/ecom-api/vipps-ecom-api/#error-codes). Present results in a separate page in the module configuration with the complete Vipps error message
|     Error Handling| Make sure users get a understandable notification if something went wrong, both administrators and customers. For POS integration present info both to cashier and customers.
|     Follow up on GitHub security/ Dependabot alerts| Will be added to pull requests and a monthly routine for updating these
|     On-site-messaging configuration| Add a configurable _On-site-messaging_ feature to ease the [Vipps on-site-messaging](https://vippsas.github.io/vipps-developer-docs/docs/APIs/checkout-api/vipps-checkout-on-site-messaging). |        



## Questions?

We're always happy to help with code or other questions you might have!
Please create an GitHub issue or pull request in the related repos or [contact us](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/contact) for general Vipps API related questions.

Sign up for our [Technical newsletter for developers](https://vippsas.github.io/vipps-developer-docs/docs/vipps-developers/newsletters/).







