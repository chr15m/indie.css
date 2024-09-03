** 🚧 Work in progress. I'm dogfooding this until it's ready for you. **

indie.css is a simple, minimal, classless* CSS stylesheet to make your site or app look good.

[Download](#download) | [Goals](#goals) | [Customizing](#customizing) | [Alternatives](#alternatives) | [Who](#who)

It's designed for indie developers who need to ship fast.

It strikes a balance between simplicity and customizeability with a handful of CSS vars.

* Note: some of the extended functionality rules (layout and inputs) use some optional classes.

### Download

<a href="indie.css"><button>indie.css (Xkb)</button></a>

### Goals

- Small
- Open source (MIT)
- No tailwind or dependencies
- Customizeable with a handful of CSS vars
- Separate styles for typography, HTML form inputs, and layout.

### Utility classes

indie.css ships with a small number of utility classes for common layouts and coloration.

### Customizing

indie.css is designed to be easy to customize with CSS vars.

You can simply override these vars with your own additional stylesheet, or an inline `<style>` tag.

Of course you can also copy the stylesheet to your own project and add to it as you like.

In dark mode the `--fg` and `--bg` variables should be swapped.

```
:root {
  --fg: #191817;
  --bg: #F2F0EB;
  --highlight: #F2F0EB;
  /* --highlight: #00666D; */
  /* --highlight: #BBB645; */
  --font: Arial, Inter, Helvetica, sans-serif;
  --font-h: Arial, Inter, Helvetica, sans-serif;
}

@media (prefers-color-scheme: dark) {
  :root {
    --fg: #F2F0EB;
    --bg: #191817;
  }
}
```

### Alternatives

indie.css is a fork of concrete.css because I liked the design.

there are a large number of similar stylesheets. None of these met the criteria above:

### Who

indie.css is built by [Chris McCormick](https://mccormick.cx).
