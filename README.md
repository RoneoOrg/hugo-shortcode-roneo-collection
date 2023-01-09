



## Enhancing Hugo with a Shortcode collection


### Use inline SVG icons

- Use 4000+ open source SVG icons with Hugo
- Easily add your own icons and define custom CSS classes

#### Screenshot

![Inline SVG icons with this shortcode for Hugo](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection/-/raw/main/img/svg-icons.png)  

#### Usage

As a shortcode:

    {{< ico moon >}}

    {{< ico icon="star" theme="solid" class="red medium" >}}

As a partial:

    {{ partial "ico" "star" }}

See this [release announcement](https://roneo.org/en/hugo-svg-icon-shortcode/) to learn more

### Embed audio files

An elegant way to insert an audio player and share local and remote audio files.

Usage:

```
{{< audio "https://archive.org/download/test/aufiofile.mp3" >}}
```
Screenshot:

<div align="center">

![Screenshot of the audio Shortcode in action](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection/-/raw/main/img/screenshot.jpg)

</div>

Options are available. Here we define a caption

```go
{{< audio "/audiofilename.mp3" "A custom comment" >}}
```

Named parameters can be used too:

```go
{{< audio src="/audiofilename.mp3" caption="A custom comment" class="foo" preload="none" >}}
```

This shortcode is based on [Plyr.io](https://plyr.io/), see [this tutorial](https://roneo.org/en/hugo/plyr) to set up with Hugo


### Customized notices and warning

Usage:

```
{{< box info >}}
  Incididunt labore eiusmod culpa eu nostrud tempor laborum consequat eiusmod excepteur.
{{< /box >}}
```

Screenshot:

![Include custom messages in your posts with a Shortcode](https://roneo.org/illustrations/hugo-notices-shortcode-show-warning-message.en-img/20220914110145.jpg)

See the [demo and documentation](https://roneo.org/en/hugo-warning-messages-shortcode/) for details.


### Embed video file

**Mission:** easily embed players from local and remote video files


Usage:

    {{< video "https://archive.org/download/tesfile.mp4" >}}


Options are available. Here we define a caption:

```go
{{< video "/testfile.mp4" "A custom caption" >}}
```

Named parameters can be used too:

```go
{{< video src="/test-file.mp4" caption="A custom comment"  poster="preview-image.jpg" class="foo" preload="none" >}}
```

This shortcode is based on [Plyr.io](https://plyr.io/), see [the documentation](https://github.com/sampotts/plyr#features) to learn about the features and [this tutorial](https://roneo.org/en/hugo/plyr) to set up with Hugo

### Include a Markdown file into another

The same content can be relevant in several places.  
Here is how to include the same Markdown file in multiple pages.

    {{% include "included-file-name.md" %}}

Features:

- Markdown content and Shortcodes are properly included and rendered
- The Front Matter of included file is hidden
- The filename is enough (no fullpath is required)

Note that you may need to restart Hugo Server to see the changes in included files applied.

See [these notes](https://roneo.org/en/hugo-include-another-file-with-a-shortcode/) for details

<!-- 
### List Github stars

**Mission**: Display a list of the last starred repositories on Github on your website. This list is automatically updated every time the website is rebuilt.

**Screenshot:**

![A screenshot of Github API shortcode for Hugo](https://roneo.org/illustrations/hugo-api-get-users-starred-repo-from-github-api-shortcode.en-img/20220914095801.jpg)


See [the demo](https://demo.roneo.app/hugo-fetch-github-api-shortcode/) for live examples and [the documentation](https://roneo.org/en/hugo-fetch-remote-data-github-api-shortcode/) for guidance.


### Embed multiple audio files from Archive.org

Usage:

    {{< archive-audio "https://archive.org/details/heyamoli" >}}

Demo: See https://phoni.es/dev/v4/

 -->


## Installation


See the [dedicated documentation](https://roneo.org/en/hugo-install-shortcode-collection/).


## Found a problem?

Please open an issue on [Github](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection/issues) / [Gitlab](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection) or [drop me an email](https://roneo.org/contact/).


## Contribute

**Code contributions are welcome**, and the main place for development is [this Gitlab repo](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection). You can use [this Github repo](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection) too.

**Please star this repo** on [Github](https://github.com/RoneoOrg/hugo-shortcode-roneo-collection) or [Gitlab](https://gitlab.com/Roneo/hugo-shortcode-roneo-collection), to help this project gain some visibility and reach new contributors.


## References

- [Hugo documentation about Theme Components](https://gohugo.io/hugo-modules/theme-components/)
- Hugo documentation about [Shortcodes](https://gohugo.io/content-management/shortcodes/)