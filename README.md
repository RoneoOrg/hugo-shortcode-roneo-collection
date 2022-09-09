
## A shortcode collection for Hugo

See the folder `layouts/shortcodes/` for details

Some highlights:

### Github stars

Fetch the last starred repo on Github, and for each repo, display the amount of stars and forks, the size of the repo and the last update

**Demo**: See [demo.roneo.app](https://demo.roneo.app/hugo-fetch-github-api-shortcode/)

**Usage**: `{{< github-api url="https://api.github.com/users/RoneoOrg/starred" >}}`

**Note**: See [this post](https://roneo.org/en/hugo-fetch-remote-data-github-api-shortcode/) for details


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