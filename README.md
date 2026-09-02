# Cab Captain App — Prototype

Interactive prototype of the Cabs Paraforce captain onboarding & compliance app, built for the client pitch.

- **`index.html`** — the deployed app. On desktop it shows the presentation shell (phone mockup + a rail to jump between screens). On a phone it drops the shell entirely and runs edge-to-edge, like a real installed app: no browser chrome bleed, safe-area-aware status/home bars, a floating screen-jump sheet instead of the desktop rail, Android back-button support, and an "Add to Home Screen" prompt (PWA manifest + service worker) so it can be launched from the home screen with no address bar at all.
- **`paraforce-captain-app-prototype.html`** — the original desktop-only version, kept for reference.
- **`manifest.webmanifest`**, **`sw.js`**, **`icon-*.png`** — PWA install support.
- **`og.png`** — link-preview card shown when the URL is shared (e.g. on WhatsApp).

No backend, no data persistence — every screen is static markup toggled by a small script. Built for a client walkthrough, not production.
