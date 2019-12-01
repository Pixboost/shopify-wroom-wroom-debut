# shopify-wroom-wroom-debut
Shopify debut theme optimised with Pixboost for wroom-wroom.myshopify.com

Original debut theme: https://wroomwroom.myshopify.com/?preview_theme_id=33132314679

# Dev

Follow [Shopify Theme Kit](https://shopify.github.io/themekit/) instructions.

I found that using MS Visual Code with this [plugin](https://github.com/GingerBear/vscode-liquid) is the best option that worked for me.

# Run

Set your private app password to the environment variable:

```
export THEMEKIT_PASSWORD=<APP_PASSWORD>
```

In two terminals:

* To preview changes: `theme open --env=development`
* To watch and upload changes: `theme watch`