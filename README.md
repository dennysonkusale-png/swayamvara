# स्वयंवर · Swayamvara

A free, single-file **marriage portfolio (biodata) builder** for Indian users. Open it in a
browser and create, customise, download and email a polished matrimonial profile — no server,
no sign-up, no build step.

![Swayamvara — the editor on the left, the live A4 portfolio preview on the right](screenshot.png)

*Swayamvara* (स्वयंवर) was the ancient Vedic ceremony in which a bride chose her own groom —
a fitting name for a tool that helps you present yourself on your own terms.

## Features

- **8-step guided form** — Basics, Family, Education & Career, Horoscope & Community,
  Lifestyle, Partner Preferences, Photos, Contact — with a live A4 preview beside it.
- **Four languages** — English, हिन्दी, मराठी and संस्कृतम् — switchable instantly without
  losing data. A separate *document language* selector lets you fill the form in English and
  export the portfolio in Marathi, and so on.
- **Template library** — 8 designs (Marathi Patta, Royal Rajwadi, Elegant Minimal, Floral
  Pastel, Modern Corporate, Temple Gold, Peacock Motif, Classic Ivory), plus accent-colour and
  typeface pickers and an optional "॥ श्री गणेशाय नमः ॥" invocation banner.
- **Exports** — PDF (multi-page A4), PNG, JPG, DOCX, and an **editable** PPTX that keeps its
  text editable in PowerPoint.
- **Email & share** — email the portfolio, share to WhatsApp, or create a self-contained
  **read-only link** that anyone can view and download. Anyone opening that link can tap
  **Edit** to load the portfolio straight into the editor and carry on from there, on their
  own device.
- **India-specific biodata fields** — gotra, rashi, nakshatra, gana, nadi, manglik status,
  mool gaon, family values, diet, and more.
- **Privacy toggles** — hide income, contact details or horoscope from the shared copy.
- **Optional extras** — save/load your data as a `.json` file, and an indicative Ashtakoot
  (36-point) Guna Milan calculator for Kundli matching.
- Autosaves to the device, mobile-first, with a clean print stylesheet.

## How to run

Download `index.html` and open it in any browser. That's it.

Or use the hosted version: **https://dennysonkusale-png.github.io/swayamvara/**

The export features (PDF/DOCX/PPTX/image) fetch a few libraries from a CDN the first time, so
they need an internet connection. Everything else works offline.

## Notes

- All data stays in your browser (`localStorage`). Nothing is uploaded anywhere.
- For one-click email sending, add your [EmailJS](https://www.emailjs.com/) keys to the
  `EMAILJS` block near the top of the script. Without keys, the app saves the PDF and opens
  your mail client instead.
- The Guna Milan calculator uses commonly published Ashtakoot tables and is indicative only.
  Please confirm with a qualified astrologer before making any decision.

## License

[MIT](LICENSE)
