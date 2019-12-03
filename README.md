# shopify-wroom-wroom-debut
Shopify [Debut](https://wroomwroom.myshopify.com/?preview_theme_id=33132314679) theme integrated with Pixboost Image CDN.

The main purpose of using Pixboost Image CDN is to improve the performance of a Shopify store. You could find performance result
comparing with original Debut theme here:

* [Homepage](./performance-reports/homepage/README.md)
* [Product Page](./performance-reports/product-page/README.md)

Demo store: [wroom-wroom.myshopify.com](wroom-wroom.myshopify.com)

We wrote a blog about integrating techniques and performance results [here](https://medium.com/pixboost/boosting-image-performance-of-your-shopify-store-d3696ac71f93?source=github).

# Installation

To install the them on your Shopify store, please follow the instruction from our [help](https://help.pixboost.com/shopify#installation).

# Developing

Follow [Shopify Theme Kit](https://shopify.github.io/themekit/) instructions.

Using MS Visual Code with [vscode-luquid plugin](https://github.com/GingerBear/vscode-liquid) works the best for us.

## Running

Set your private app password to the environment variable:

```
export THEMEKIT_PASSWORD=<APP_PASSWORD>
```

In two terminals:

* To preview changes: `theme open --env=development`
* To watch and upload changes: `theme watch`

# Building a release

* To build a release zip
    `zip -r debut-pixboost-<VERSION>.zip . -x@package_exclude.lst`
* Create a new release in github and attach a zip created in the above step