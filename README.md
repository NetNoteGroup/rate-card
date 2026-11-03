# Daniel Kariuki Githua – Digital Rate Card

A mobile-friendly digital rate card for **Daniel Kariuki Githua**, IT Solutions Architect & Network Engineer (NetNote Group). Clients browse services and starting prices, then tap **Request quote** to message me on WhatsApp with the service already filled in.

🔗 **Live rate card:** https://netnotegroup.github.io/rate-card/

## Features

- Services grouped into five tabs:
  - CCTV & Security
  - Networking & IT Support
  - Websites & Software (including NFC + QR digital business cards)
  - Branding & Design
  - Robotics & Drones
- Fixed prices, "From" prices, and "Request a quote" for jobs that depend on scope
- One-tap **Request quote** buttons that open WhatsApp with the service name and price in the message
- Quick contact buttons for WhatsApp, call and email
- Automatic light and dark mode
- Responsive on phones, tablets and desktops
- Single file, no frameworks and no build step

## Files

```
ratecard/
├── index.html   # The whole rate card (HTML, CSS, JS, photo included)
└── README.md
```

## Run locally

Open `index.html` in any browser. No installation needed.

## Edit prices and services

Open `index.html` and find `const RATES=[`. Each service is one line:

```js
{c:"Websites & Software",n:"Service name",d:"Short description.",p:"From KSh 10,000"},
```

- `c`: category tab (must match exactly to appear in that tab; a new name creates a new tab)
- `n`: service name
- `d`: short description
- `p`: price text. Delete `p:` to show "Request a quote".

Every line except the last must end with a comma.

## Change contact details

Search `index.html` for `254798232855` (WhatsApp and phone number) and the email addresses, then replace them with your own.

## Deploy

Works on any static host:

- **Cloudflare Pages / Netlify:** drag and drop the folder
- **GitHub Pages:** Settings → Pages → deploy from the `main` branch, root folder

Tip: share the link in your WhatsApp status, TikTok bio and email signature.

## Contact

- WhatsApp: [+254 798 232 855](https://wa.me/254798232855)
- Telegram: [@Aj_aq9](https://t.me/Aj_aq9)
- Email: kariukid238@gmail.com · netnotechronicles@gmail.com
- TikTok: [@netnote.chronicle](https://www.tiktok.com/@netnote.chronicle)

## License

© 2026 Daniel Kariuki Githua. All rights reserved.
