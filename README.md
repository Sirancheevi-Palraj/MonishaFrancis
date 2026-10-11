# Monisha & Francis Amalraj — Wedding Invitation

A mobile-responsive Christian wedding invitation website for **Wednesday, 21 October 2026**.

- Wedding: 4:30 PM onwards
- Reception: 7:00 PM onwards
- Venue: GiriAm Party Hall (A/C)
- Google Maps: https://maps.app.goo.gl/U7y6oPdKiY9cd4r46?g_st=ac
- Includes a venue QR code, an ICS calendar reminder (one-day alarm), sharing action, and Zetchain Instagram credit.

## Deployment

The GitHub Actions workflow at `.github/workflows/deploy.yml` automatically deploys the static website to GitHub Pages when changes are pushed to `main`, or when manually started from the Actions tab.

**One-time setup:** In GitHub, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. After that, pushes to `main` deploy automatically.

## Run locally

Open `index.html` in a browser. Keep the `assets` directory beside it. The QR code is a static SVG in that directory.
