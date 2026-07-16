# Office Food — Bill Splitter 💸

A tiny, single-file web app to work out who owes what after someone pays for a shared meal.

**🔗 [Preview the live site »](https://harting02.github.io/Office-Food/)**

> Requires GitHub Pages to be enabled (Settings → Pages → Deploy from branch → `main` / root).

## Features

- **Custom per person** — each person enters their own share (what they actually ordered).
- **Even split** — divide one total equally.
- **Service charge** — default 10%, split **evenly** between everyone.
- **Service tax** — default 6%, charged on each person's share plus their portion of the service charge (Malaysian SST order: subtotal + service charge).
- **Who paid** — pick the payer; everyone else sees what they owe, and the payer sees what they get back.
- **Payment QR** — shows the payer's QR so others can scan and pay. Bake QRs into the repo (see [`qr/`](qr/)) or upload one per person in-app.
- **Share / save** — generates a summary image (who owes what, for what, paid to whom) with the payer's QR, ready to send to the group chat. Also copies a text summary.
- Currency: **MYR (RM)**.
- Auto-saves in your browser (localStorage). Works offline. Mobile-friendly.

## Use it

Open `index.html` in any browser — no install needed.

If GitHub Pages is enabled for this repo, it's live at:
`https://harting02.github.io/Office-Food/`
