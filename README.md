# NetzFinder — GitHub Pages

Static landing page to find a German address's postal code and continue to a public electricity network-operator finder.

## What works
- Responsive landing page in German.
- Accepts a German address or a 5-digit postcode.
- For addresses, uses the public OpenStreetMap Nominatim geocoding service to obtain a postcode.
- Offers links to the EMA Energiewelt Netzbetreiber-Finder, VNBdigital and OpenStreetMap.

## Important limitation
This starter does **not** contain a complete network-area database and does not claim to determine the responsible operator itself. The postcode must be checked in the external finder. Public MaStR-derived lookups are generally based on postcode/municipality and may not be exact to the house number. For a binding answer, check the electricity bill or ask the network operator.

## Deploy for free on GitHub Pages
1. Create a new **public** repository on GitHub, e.g. `netzbetreiber-finder`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub to publish the site. It will be available at `https://YOUR-USERNAME.github.io/netzbetreiber-finder/`.

No API key or backend is required. Nominatim has a usage policy and is a community service; do not use this frontend for high-volume automated requests.
