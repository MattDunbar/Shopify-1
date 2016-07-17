Shopify NewSpring
=====================

This theme is a modification of the [Timber](http://shopify.com/timber) theme by shopify for the [NewSpring Store](https://newspring-store.myshopify.com).

Get Started
---------------------
- Clone the repo `git clone https://github.com/NewSpring/Shopify.git`
- run `gem install shopify_theme` to install Shopify's theme tools
- from inside the Shopify directory, run `theme configure <API Key> <Password> newspring-store.myshopify.com`
  - Get the api key and password from the admin control panel under `Admin > Apps > Private Apps > Dev`
  - Enter the key and password without the <>

Editing
---------------------
- Launch terminal and run `theme watch`
  - This watches for changes and automatically uploads the changes to the store when a file is saved.
- Alternatively, you can just run `theme upload` after every change you want to test

Documentation
---------------------
Visit the [Timber's Documentation](http://shopify.com/timber) page to find out more about the base theme, and supporting JS.

Basic structure
---------------
```
├── assets
│   └── Javascript, CSS, and theme images
├── layout
│   ├── theme.liquid
│   └── optional alternate layouts
├── snippets
│   └── custom code snippets
├── spec
│   └── tests and helpers
├── templates
│   ├── 404.liquid
│   ├── article.liquid
│   ├── blog.liquid
│   ├── cart.liquid
│   ├── collection.liquid
│   ├── collection.list.liquid
│   ├── index.liquid
│   ├── list-collections.liquid
│   ├── page.contact.liquid
│   ├── page.liquid
│   ├── product.liquid
│   ├── search.liquid
│   └── customers
│         └── required templates if customer accounts are enabled
├── config.yml
│   └── if using the theme gem (see link under Additional Resources)
```

Additional resources
---------------------
- [Themes Documentation][1]: Learn more about Liquid and theme templates.
- [Theme Gem][2]: Run the command line for a more intimate way of managing your theme files.
- [Theme Kit][7]: Next generation tool for syncing theme files. Currently in beta.
- [Liquid Tag Cheat Sheet][4]
- [Retail Tours][5]: Sign up for a workshop in a city near you to learn all things Shopify.
- Need more help? Ask a question in our [Design Forums][6].

License
---------------------
Timber is released under the [MIT License](LICENSE).

[1]: http://docs.shopify.com/themes
[2]: https://github.com/Shopify/shopify_theme
[3]: http://apps.shopify.com/desktop-theme-editor
[4]: http://cheat.markdunkley.com
[5]: https://www.shopify.com/retailtour
[6]: http://ecommerce.shopify.com/c/ecommerce-design
[7]: https://github.com/Shopify/themekit
