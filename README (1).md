# Fortune Web Solutions (rebuilt)

One file: `index.html`. Styles and scripts are inside it, and all the text is in the HTML so Google can read it and the page loads instantly.

## Before going live (in this order)
1. **Connect the quote form.** Open index.html, find `SITE SETTINGS` near the bottom and fill in:
   - `whatsapp`: your number in international format, no + or spaces (e.g. 27821234567). Leads open in WhatsApp, ready to send to you.
   - `formspree` (optional): create a free form at formspree.io and paste its link to also get each lead by email.
   - `email`: an inbox you have actually tested. hello@fortunedigital.co.za only works if you own that domain.
   Until one of these is set, the form shows a "Setup needed" message instead of pretending to send.
2. **Test it from your phone.** Send yourself a quote request and check it arrives.
3. **Domain and hosting.** Upload index.html to GitHub Pages (or Netlify), then connect your own .co.za domain.
4. **Link previews.** Replace YOUR-DOMAIN.co.za in the og: tags at the top and upload a 1200x630 image named preview.jpg.
5. **Meta Pixel (before ads).** Paste the Pixel code from Meta Events Manager where it says META PIXEL. The form already sends a Lead event when someone submits.
6. **Portfolio.** Only keep EconoBEE if you built it and have permission to show it. Add real projects as you finish them.
7. **Instant lead replies price.** It shows "Quote" for now. Set a price once you know your setup and monthly running costs.

## What changed from the old version
- Quote requests now reach you (WhatsApp/email) instead of being saved on the customer's phone.
- Removed the fake client portal.
- Asks for a phone/WhatsApp number, not just email.
- Added the instant lead replies service, a "how it works" section and a live demo.
- Bottom nav only on phones; desktop gets a normal top menu.
- Dark mode, keyboard focus, readable text sizes.
- Removed manifest.json and sw.js. The offline/install feature was never switched on, so they did nothing.
