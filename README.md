
## A shortcode collection for Hugo




### Github stars

**Objective**: Get a list of the last starred repositories on Github, automatically updated every time the website is rebuilt.

**Screenshot:**

![A screenshot of Github API shortcode for Hugo](https://roneo.org/illustrations/hugo-api-get-users-starred-repo-from-github-api-shortcode.en-img/20220909004638.jpg)


**Demo**: See [demo.roneo.app](https://demo.roneo.app/hugo-fetch-github-api-shortcode/) for live examples.

**Usage**: `{{< github-api url="https://api.github.com/users/RoneoOrg/starred" >}}`

**Details**: See [the documentation](https://roneo.org/en/hugo-fetch-remote-data-github-api-shortcode/).


## Installation

Install the collection as a Git submodule:

```bash
git submodule add https://gitlab.com/Roneo/hugo-shortcode-roneo-collection.git themes/hugo-shortcode-roneo-collection
```

Then edit your [configuration file](https://gohugo.io/getting-started/configuration/) this way:

```toml
theme = ["hugo-shortcode-roneo-collection", "YourCurrentTheme"]

enableInlineShortcodes = true
```

## Found a problem?

Please open an issue on [Github](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection/issues) / [Gitlab](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection) or [drop me an email](https://roneo.org/contact/).


## Contribute

**Code contributions are welcome**, and the main place for development is [this Gitlab repo](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection). You can use[this Github repo](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection) too.

**Please star this repo** on [Github](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection) or [Gitlab](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection), to help this project gain some visibility and reach new contributors.


## References

-   [Hugo documentation about Theme Components](https://gohugo.io/hugo-modules/theme-components/)
-   Hugo documentation about [Shortcodes](https://gohugo.io/content-management/shortcodes/)