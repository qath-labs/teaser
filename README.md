# qath — teaser

The holding page for [qath.ai](https://qath.ai/), served while the real thing is being built.

A single static `index.html` with no build step: Tailwind runs from the CDN and Figtree is loaded from Google Fonts. Drop the folder on any static host and it works.

## Files

| File           |                                                      |
| -------------- | ---------------------------------------------------- |
| `index.html`   | The whole page — markup, Tailwind config, custom CSS |
| `og-image.png` | Social preview, 1200×630                             |
| `icon.svg`     | Favicon, adapts to light/dark browser chrome         |
| `favicon.ico`  | Fallback favicon for older browsers                  |

## Local development

Open `index.html` in a browser, or serve the folder if you want absolute paths to resolve the way they will in production:

```bash
python3 -m http.server 8000
```

## Notes

- The page targets WCAG AA contrast, and honours `prefers-reduced-motion` and Windows High Contrast Mode. Worth keeping in mind when adjusting colours or the gradient headline.

## License

MIT — see [LICENSE](LICENSE).
