# Payment QR codes

Drop each person's payment QR image here so the app can show it automatically
when they're selected as the payer.

## Naming rule

The filename must be the person's **name in lowercase with all spaces and
symbols removed**, ending in `.png`. The name must match what you type in the
app's *People* list.

| Name in the app | File to add        |
| --------------- | ------------------ |
| `Marcha`        | `qr/marcha.png`    |
| `John Doe`      | `qr/johndoe.png`   |
| `Ali B.`        | `qr/alib.png`      |

## Notes

- Use a clear, square-ish crop of just the QR (a phone screenshot of your
  DuitNow / bank QR is fine). PNG keeps it sharp and scannable.
- These are committed to the repo, so anyone opening the site sees them.
  Only add QRs you're happy to share publicly.
- A person can still override the baked-in QR by uploading one via the
  **+ QR** button in the app (that upload stays only on their device).
