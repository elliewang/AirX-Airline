# AirX — Airline Booking Website + Travel Assistant

A polished **100% static** airline booking portfolio demo that works on **GitHub Pages**. No npm, Node server, database, API key, or build step is required.

## Features

- Responsive airline landing page and popular destinations
- Demo flight search by city, date, trip type, passengers, and cabin
- Generated sample flights and fares (**not real flight inventory**)
- Demo booking confirmation and cancellation saved to the browser using `localStorage`
- Browser-only conversational travel assistant with route recognition
- Keyboard-friendly dialogs and mobile layouts

## Deploy to GitHub Pages

1. Create a public GitHub repository named `airx-github-pages` (or any name).
2. Upload **all** files in this folder to the **repository root** (`index.html`, `styles.css`, `app.js`, etc.). Do not upload the ZIP itself.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)**. Click **Save**.
5. After deployment completes, open the Pages URL shown by GitHub, typically `https://YOUR_USERNAME.github.io/airx-github-pages/`.

If you prefer Actions deployment, `.github/workflows/pages.yml` provides that workflow; choose **GitHub Actions** as the Pages source instead of **Deploy from a branch**. Do not configure both methods simultaneously.

## Run locally

Open `index.html` in your browser. You can also use VS Code Live Server if preferred.

## Project layout

```
index.html                Main website
styles.css                Responsive styling
app.js                    Search, demo bookings, travel assistant
.github/workflows/pages.yml  Optional GitHub Pages deploy workflow
.nojekyll                 Static asset support
```

## Important limitations

This is a front-end **portfolio demonstration**, not a commercial airline booking service. Prices and schedules are generated samples. Reservations exist only in the browser where created and can disappear if browser storage is cleared. The agent is **rule-based**, not connected to a real LLM. No real inventory, payments, login, or tickets are available. Do not enter sensitive personal data.

For a production airline platform, add secure server-side bookings, real flight inventory APIs, payment processing, identity, durable storage, and a hosted AI agent.
