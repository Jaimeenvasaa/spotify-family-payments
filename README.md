# Spotify Family UPI payment pages

- `het.html`: Het, ₹90
- `ashutosh.html`: Ashutosh, ₹30

Both pages use UPI ID `jaimeenvassa-1@oksbi` and note `Spotify Monthly Plan`.

## Publish free using GitHub Pages
1. Create a public GitHub repository named `spotify-family-payments`.
2. Upload both HTML files to the repository root.
3. Open Settings → Pages.
4. Select Deploy from a branch, choose `main` and `/ (root)`, then Save.
5. After publishing, use:
   - `https://YOUR-USERNAME.github.io/spotify-family-payments/het.html`
   - `https://YOUR-USERNAME.github.io/spotify-family-payments/ashutosh.html`

Test on the recipients' actual phones before using the links in scheduled SMS.

## Notes
No gateway is used. Android generally supports the generic `upi://pay` app chooser. iPhone requires app-specific schemes and behavior varies by app/browser; the included app buttons are not guaranteed on every device. The page cannot verify payment; check your UPI/bank app. Never enter a UPI PIN on this webpage.
