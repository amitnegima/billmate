# BillMate — Free Invoice Generator for Indian Shops

A 100% free, client-side invoice and bill generator built for Indian shopkeepers and small businesses. No signup, no server, no ads — everything runs in your browser.

## Features

- **Instant PDF invoices** — Professional bills with shop name, items, GST breakdown, payment details
- **GST support** — IGST/CGST+SGST, buyer/seller GSTIN, HSN code, Place of Supply
- **UPI QR code** — Auto-generated payment QR on bills
- **Auto invoice numbering** — Configurable prefix, start number, padding
- **Item catalog** — Searchable dropdown with customizable items and prices
- **Bill history** — All finished bills saved in browser, exportable as CSV
- **Walk-in customers** — Create bills without entering customer name
- **Works offline** — All data stored in localStorage, no internet needed after first load

## Tech Stack

- Single HTML file (~1300 lines)
- Vanilla JavaScript — no framework, no build step
- [jsPDF](https://github.com/parallax/jsPDF) + [AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) for PDF
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) for UPI QR
- [Inter](https://fonts.google.com/specimen/Inter) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) fonts

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the repo
4. Deploy — no build command needed

Or use the CLI:
```bash
npx vercel --prod
```

## Files

```
billmate/
├── index.html      # The entire app
├── vercel.json     # Vercel routing + headers
└── README.md       # This file
```

## Support

- Email: amitnegimca@gmail.com
- If BillMate helps your business, consider donating via UPI: `amitnegimca@oksbi`

## License

Free to use. Made with care for Indian shopkeepers.
