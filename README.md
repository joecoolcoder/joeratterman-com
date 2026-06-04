# Joe Ratterman Static Website

This is a simple static website. It can be uploaded to GoDaddy with ordinary file transfer.

## Files

- `index.html` is the home page.
- `websites.html`, `resources.html`, and `about.html` are the other pages.
- `css/styles.css` controls the layout, spacing, colors, and mobile behavior.
- `images/` contains the graphics used by the site.
- `files/` contains downloadable PDFs and ZIP files used by the Resources page.

## Common Edits

To change page text, open the matching `.html` file and edit the text inside the main content area.

To replace the home page graphic, put the new image in `images/` and update this line in `index.html`:

```html
<img src="images/main-graphic.webp" alt="...">
```

To replace the top logo graphic, put the new image in `images/` and update this line on each page:

```html
<img class="site-logo" src="images/joeratterman.webp" alt="joeratterman.com">
```

To change colors, spacing, menu size, or mobile layout, edit `css/styles.css`.

## Upload

Upload these files and folders together:

- all `.html` files
- `css/`
- `images/`
- `files/`
