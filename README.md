
## A shortcode collection for Hugo

Mostly imported from [Beautifulhugo](https://github.com/halogenica/beautifulhugo) to maintain compatibility during a migration.

See the folder `layouts/shortcodes/` for details



### Github stars

Display the last starred repo on Github

Usage:

    {{< github-api url="https://api.github.com/users/RoneoOrg/starred" >}}

**Note**: Github API calls are limited and the build breaks when limits are reached.
Ignore related with `ignoreErrors: error-remote-getjson` in your config file.

See https://gohugo.io/templates/data-templates/
