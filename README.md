# Miserably Employed Theme

This is the theme for miserablyemployed.com.

## Using this theme

To make changes to the theme and run it locally, you'll need to install shopify's cli: https://shopify.dev/docs/api/shopify-cli

Once you have that installed, you can login locally with:

``` sh
shopify theme dev --store miserably-employed-dev
```

It will prompty you to login via the browser and will authenticate you. Once you've logged in, it will return you to the terminal.

You'll then be able to view your local instance at http://127.0.0.1:9292

### Uploading to the store

To push the new theme to the shopify store for the first time, you'll use:

```sh
shopify theme push --unpublished
```

You'll be prompted to provide a name.

After the theme is created, you can update your theme code by running the push command without any flags:

```sh
shopify theme push
```

### Publish

Once you're ready, you can publish with:

```sh
shopify theme push
```


## License

This theme is a fork of Dawn, which is provided by Shopify.
Copyright (c) 2021-present Shopify Inc. See [LICENSE](/LICENSE.md) for further details.
