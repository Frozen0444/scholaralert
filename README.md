# ScholarAlert – Final MVP

A mobile-first, installable web app prototype for personalized scholarship discovery.

## Try it fast
Open `index.html` in Chrome. For full install/PWA behavior, serve this folder from a local/static HTTPS server. On Android Chrome: menu → Add to Home screen.

## Included
- Multi-user-ready profile model (local device profile in this MVP)
- Personalized scholarship matching
- Search, save, deadline countdown
- Official NSP application links
- Notification permission test
- Responsive Android-style UI
- Current NSP 2026–27 discovery dataset seeded from the official portal

## Production upgrade
Connect Firebase/Supabase for accounts and database, then use Firebase Cloud Messaging (FCM) or Web Push for real background notifications. A server-side collector should periodically verify official scholarship sources, normalize eligibility, and create alerts.

## Important
The app does not claim that a user is definitely eligible. It shows possible matches and sends users to the official scheme page to verify all conditions before applying.
