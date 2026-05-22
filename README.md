# Spark Designs

Static gallery of generated mobile UI design explorations for Spark learning-gap examples.

Live site: https://spark-designs.pages.dev/

## Files

- `index.html` is the Cloudflare Pages entrypoint.
- `gallery.html` is kept as the editable gallery source mirror.
- `images/*.png` contains the generated design images, named from the visible gallery number and title.
- `designs-review-ui-task.md` is the original design-generation brief for this gallery.

## Deploy

```sh
npx --yes wrangler@latest pages deploy . --project-name spark-designs --branch main
```
