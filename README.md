
## A shortcode collection for Hugo

See the folder `layouts/shortcodes/` for details

Some highlights:

### Github stars

Display the last starred repo on Github

**Demo**: See [demo.roneo.app](https://demo.roneo.app/hugo-fetch-github-api-shortcode/)

**Usage**: `{{< github-api url="https://api.github.com/users/RoneoOrg/starred" >}}`

**Note**:

Github API calls are limited and the build breaks when limits are reached.  
You can ignore related errors with `ignoreErrors: error-remote-getjson` in your config file.  
See also Cache Handling in [Hugo's documentation](https://gohugo.io/templates/data-templates/)


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
To learn more about "Theme components", see [the Hugo documentation](https://gohugo.io/hugo-modules/theme-components)


## Contribute

**Code contributions are welcome**, and the main place for development is [this Gitlab repo](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection). Feel free to use [this Github repo](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection).

**Please star this repo** on [Github](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection) or [Gitlab](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection), to help this project gain some visibility and reach new contributors.


## References

-   [Hugo documentation about Theme Components](https://gohugo.io/hugo-modules/theme-components/)
-   Hugo documentation about [Shortcodes](https://gohugo.io/content-management/shortcodes/) 