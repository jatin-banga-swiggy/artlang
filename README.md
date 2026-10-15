# ArtLang runtime

The built ArtLang runtime: the page components, their styles and themes, and Chart.js, in one file.
Load it in the `<head>` of an ArtLang page, pinned to a release tag:

```html
<script src="https://cdn.jsdelivr.net/gh/jatin-banga-swiggy/artlang@v0.3.3/artlang.js"></script>
```

Each release is a git tag (`v0.3.0`, `v0.3.1`, `v0.3.2`, `v0.3.3`, …). Always use a tagged URL, never a branch, so published
pages keep working when a new version ships.

Includes Chart.js and @kurkle/color (both MIT licensed); their licence notices are at the end of
`artlang.js`.
