# NYL Language Selector

A mobile-first static landing page for GitHub Pages.

## Update a destination URL

Open `index.html`, find the desired language button, and replace its `href` value.

Example:

```html
<a class="language-button" href="https://example.com/spanish">
  <span class="language-name">Español</span>
</a>
```

For the Spanish button, also remove `data-needs-url="true"` after adding the real URL.

## Add another language

Find one of the future-language examples in `index.html`:

```html
<a class="language-button" href="#" hidden>
  <span class="language-name">中文</span>
</a>
```

1. Replace `#` with the destination URL.
2. Remove the `hidden` attribute.
3. Change the displayed language name if needed.

## Publish

Use GitHub Pages with the `main` branch and the repository root folder.
