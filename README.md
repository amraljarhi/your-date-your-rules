# Your Date, Your Rules 🙃

A lightweight, playful, mobile-first date invitation for Lara.

## Open locally

Open `index.html` in a browser. No build step, dependencies, or server required.

## Publish with GitHub Pages

1. Create a **public** GitHub repository named `your-date-your-rules`.
2. Add the supplied `index.html` and `README.md` to the root of the repository.
3. In repository **Settings → Pages**, select **Deploy from a branch** and choose `main` / `(root)`; save.
4. Once deployment completes, the site should be at `https://YOUR-USERNAME.github.io/your-date-your-rules/`.

Do not include private chat messages or sensitive personal data in this public repository.

## WhatsApp destination

The final button opens WhatsApp with all selections prefilled, using the share/contact chooser by default. Lara can choose the person to send to.

If you want to pre-address it, set `CONFIG.recipientNumber` near the beginning of the JavaScript, e.g. `recipientNumber: '316...'` (international format, digits only). **This will expose the number publicly in the site's HTML source.** Consider keeping the chooser instead for privacy.

The secondary **Copy instead** button copies the same message to the clipboard (with a fallback for less permissive browsers).

## Customize

All question text and choices are stored near the start of the `questions` JavaScript array. Scheduling options are currently **Tuesday Nov 3 and Wednesday Nov 4, 2026** in Denmark time. Update them if the date changes.

No personal data is collected or stored on a server. The only storage is a one-time session celebration marker.