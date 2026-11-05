# Scalar Code — Demo builds

Concept websites built by [Scalar Code](https://scalarcode.vercel.app) to show future clients what their site could look like. Every demo is fully clickable: carts, filters, search, checkout and bookings all work (nothing is charged or booked).

| Demo | Type | Highlights |
| --- | --- | --- |
| [Atelier Nord](demos/shop/) | E-commerce (clothing) | Product filters & sorting, quick view with size picker, slide-out bag, free-shipping bar, checkout |
| [FreshCorner Market](demos/market/) | Grocery / market | Search, categories, daily deals countdown, live basket, delivery time slots, order tracking |
| [Brasa](demos/restaurant/) | Restaurant | Animated hero, filterable menu (vegetarian / gluten-free / spicy), opening hours, table reservations |

The root `index.html` is a showcase page linking to all demos with live previews.

## Run locally

No build step, just plain HTML, CSS and JavaScript.

```bash
python3 -m http.server 5173
```

Then open http://localhost:5173.

## Deploy

Import this repo into Vercel (framework preset: **Other**), or enable GitHub Pages on the `main` branch.

---

Got a website that needs building? scalarcode@outlook.com
