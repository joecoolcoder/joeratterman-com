# Joe Ratterman Static Website

This is a simple static website. It can be uploaded to GoDaddy with ordinary file transfer.

## Files

- `index.html` is the home page.
- `about.html`, `resources.html`, `projects.html`, and `files.html` are the main interior pages.
- `angel-flight.html` and `world-record.html` are starter pages linked from Projects.
- `css/styles.css` controls the layout, spacing, colors, and mobile behavior.
- `images/` contains the graphics used by the site.
- `site-files/` contains PDFs and ZIP files linked from public site pages such as Resources.
- `files/` is reserved for ad hoc shared downloads linked from the Files page.

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
- `site-files/`
- `files/`
