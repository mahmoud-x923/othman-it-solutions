# Othman IT Solutions – Angebote

Client offer pages for **Othman IT Solutions** ([othmanit.dev](https://othmanit.dev)): websites and social media for restaurants, cafés and small businesses in Dortmund. The pages are hosted on GitHub Pages.

## Pages

| Path | Client |
|---|---|
| `/shawarma-togo/` | Shawarma TOGO, Dortmund (website + social media offer) |

The site's home page (`/`) redirects to the current offer for now.

## What the offer page includes

- **Four packages:** Start, Sichtbar, Premium and Rundum. Tap a package to select it, and the summary at the bottom updates.
- **Language switch:** German, English and Arabic. In Arabic the layout reads right-to-left.
- **Launch discount:** none, −10%, −15% or −20%. Discounted one-time prices are rounded to the nearest 10 €. The monthly fees aren't discounted.
  - Tap **✓** to collapse the discount options, so only the chosen discount shows.
  - **Press and hold** the badge or the "Die Pakete" heading for about a second to show the options again. Reloading the page also resets them.
- **Payback calculator:** sliders for extra customers per day, average order and open days. It shows how many weeks the selected package takes to pay for itself.
- **Extras, the 4-step process and terms**, plus a link to the [demo website](https://mahmoud-x923.github.io/shawarma-togo-demo/).

## Hosting on GitHub Pages

1. Go to **Settings → Pages**.
2. Under **Source**, choose *Deploy from a branch*, then **Branch:** `main`, folder `/ (root)`, and save.
3. The offer goes live at `https://mahmoud-x923.github.io/othman-it-solutions/shawarma-togo/`.

## Adding a new client

Copy `shawarma-togo/` to a new folder, such as `cafe-xyz/`. Then edit the client name, the packages (the `P` / `PEN` arrays), the extras (`AD`) and the texts (`T`) in the `<script>` block of its `index.html`.

> Note: this repo is public, so anyone with the link can see the prices.
