# Campus Market

Campus Market is a student-focused marketplace for buying and selling useful items within a campus community. The current project is the responsive homepage foundation for the marketplace.

## Homepage

The homepage includes:

- A campus marketplace hero section with search
- Navigation for discovery, categories, and how the platform works
- Category shortcuts for textbooks, furniture, electronics, clothing, and more
- Fresh listing cards with price and campus location details
- Trust and safety messaging for campus buyers and sellers
- Responsive layouts for desktop and mobile screens

## Project files

```text
homepage.html   Homepage structure and content
styles.css      Responsive layout and visual styling
README.md       Project documentation
```

## Run locally

This is a static HTML and CSS project. Open `homepage.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 4173
```

Then visit <http://localhost:4173/homepage.html>.

## Current status

The current version focuses on the homepage UI. Search, authentication, saved items, selling, and marketplace data are represented visually but are not connected to a backend yet.

Product images are loaded from Unsplash and the page loads Manrope, DM Mono, and Playfair Display from Google Fonts when an internet connection is available.

## Next steps

- Connect search to real marketplace listings
- Add authentication and campus verification
- Add listing creation and item detail pages
- Add saved items and messaging between buyers and sellers