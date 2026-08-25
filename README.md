# ReWear — Clothing Exchange & Swap Marketplace

A functional Phase-1 demo website based on the provided project requirements.

## Included pages
1. Home
2. Login
3. Clothing Listings
4. Item Details
5. Swap Request
6. Negotiation Chat
7. User Dashboard
8. Admin Panel

## Functional features
- Registration/login demo with browser localStorage
- Realistic clothing seed data
- Search and category/size/condition filters
- Item details
- Swap requests
- Negotiation chat
- Swap value calculator
- Location-aware listing data/filtering
- User dashboard
- Add new clothing listing
- Admin listing moderation and analytics
- Responsive design
- No external database required for this demo

## Run locally
Open `index.html` directly in a browser, or use a static server:

```bash
python -m http.server 5500
```

Then open `http://localhost:5500`.

## Deployment
This project is static and can be deployed to Vercel, Netlify, GitHub Pages, or any static hosting provider. For a production submission, connect the UI to a secure Node.js/Express API and MongoDB/PostgreSQL, add server-side authentication, cloud image storage, and real courier integration.

## Important
The included authentication and data storage are intentionally browser-local for a zero-configuration demonstration. They are not suitable for production credentials or sensitive user data.
