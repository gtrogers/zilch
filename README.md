# Zilch CSS

Sensible website styles with zero CSS classes.

Just write semantic HTML and follow a few sensible defaults...

## Installation

### Hosting yourself
Download the latest CSS file from the [releases](https://github.com/gtrogers/zilch/releases)
and link to it in your HTML file

```HTML
<link rel="stylesheet" href="{where-ever-you-keep-your-static-content}/zilch.css">
```

### CDN

Coming soon...

## Theme

Include a short `style` element in your HTML to set some basic CSS variables and, optionally, define a [@font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face).

```HTML
<style>
    @font-face {
        font-family: "some-font";
        src: url("/path/to/some-font");
    }

    body {
        --font-family: "some-font";
        --light: #f8f8f8;
        --dark: #202022;
        --interactive-light: "";
        --interactive-dark: "";
    }
</style>
```

## Documentation

See [the website](https://gtrogers.github.io/zilch/#the-basics)
