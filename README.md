# JOWA Bakery website

A responsive, single-page bakery website built from the Instagram profile screenshot supplied in the conversation.

## Preview locally

From this folder, run:

```powershell
python -m http.server 8765
```

Then open <http://127.0.0.1:8765>.

## Publish with GitHub Pages

The included GitHub Actions workflow deploys this folder when changes are pushed to `main`. In the repository settings, choose **Pages → Build and deployment → Source → GitHub Actions**. The first workflow run then publishes the site at the Pages URL shown in the repository's Actions deployment summary.

## Content choices

- Brand, Instagram handle, Korean bakery description, donuts, Lemon Munchkins, kimbap, and Kapsoya Business Park come from the supplied profile screenshot.
- The first visual draft uses crops from that screenshot for product imagery. Replace them with original, high-resolution product photos when available.
- The Instagram gallery is a static preview, not a live Instagram feed.
- The website links orders and Korean-food reservations to Instagram. It does not claim unverified opening hours, prices, delivery, or phone details.
- The directions link opens a map search for Kapsoya Business Park; confirm the exact storefront pin before launch.

## Files

- `index.html` — page content and metadata
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and subtle scroll reveals
- `assets/` — product previews and favicon
