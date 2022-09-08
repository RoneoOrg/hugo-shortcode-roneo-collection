
## A shortcode collection for Hugo

See the folder `layouts/shortcodes/` for details



### Github stars

Display the last starred repo on Github

Usage:

    {{< github-api url="https://api.github.com/users/RoneoOrg/starred" >}}

**Note**: Github API calls are limited and the build breaks when limits are reached.
Ignore related with `ignoreErrors: error-remote-getjson` in your config file.

See https://gohugo.io/templates/data-templates/


## Installation

(Requires Hugo > 0.42)

Install as a Git submodule:

```
git submodule add https://gitlab.com/Roneo/hugo-shortcode-roneo-collection.git themes/hugo-shortcode-roneo-collection
```

Edit `config.toml`:

```
theme = ["hugo-shortcode-roneo-collection", "YourCurrentTheme"]
enableInlineShortcodes = true
```
To learn more about "Theme components", see [the Hugo documentation](https://gohugo.io/hugo


## Contribute

Code contributions are welcome, and the main place for development is [this Gitlab repo](hugo-shortcode-roneo-collection). Feel free to use [this Github repo](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection).
