# NewPicks starter storefront

This is the first, static storefront stage for NewPicks.

## Included now
- Responsive home page
- Product cards and category filters
- Product search
- Shopping cart with quantity controls
- Cart saved in the visitor's browser with localStorage
- Nigerian naira display

## Important limitation
This starter is a front-end demonstration. It does **not** yet process real payments, create customer accounts, save orders to a server, manage stock, or provide seller accounts. Do not accept customer payments or sensitive personal information through this demo. Those features require a secure backend and payment-provider integration.

## Files
- `index.html` — page structure
- `styles.css` — layout and visual design
- `app.js` — products, search, category filtering and cart

## Publish on GitHub Pages
1. Open the `Amure-more/New-Wave` repository.
2. Select **Add file → Upload files**.
3. Upload `index.html`, `styles.css`, `app.js`, and `README.md` into the repository's top level (not inside another folder).
4. If GitHub asks, commit directly to `main`.
5. Open **Settings → Pages** and confirm deployment is from `main` and `/ (root)`.
6. Wait for the deployment to finish, then open `https://amure-more.github.io/New-Wave/`.

## Next production stages
1. Confirm the product catalogue, product photos, prices and delivery regions.
2. Add a backend/database for products, users, stock and orders.
3. Integrate a payment provider such as Paystack or Flutterwave using server-side verification. Never put secret keys in browser JavaScript or a public GitHub repository.
4. Add admin and seller dashboards, order management, delivery and refunds.
5. Test payments and order flows before launch.

For a full custom marketplace, use a backend host and database; GitHub Pages alone only serves static files. Vercel can deploy an application directly from a connected GitHub repository.
