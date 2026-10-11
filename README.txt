YS Scholaria website - every page is self-contained (styles, scripts and images are inside the file), so it also opens correctly from a phone file manager. Upload all .html files to your host (index.html at the root).
- Payment logos are embedded in the pages. Optional when hosted: assets/qr/<id>.png (your merchant QR codes: bkash, nagad, upay, rocket, nexuspay, cellfin, dbbl, ibbl) appear on payments.html automatically.
- To edit prices, promo codes, payment links or the RedotPay card display, search a page for: var CAT=, PROMOS={}, PAYLINKS={}, CARD_FULL. Prices and codes are repeated in every page, so change them in all files (or ask for a rebuild).
- Accounts, requests and payment history live in each visitor's own browser. A real payment gateway and shared accounts need a backend (for example SSLCommerz, aamarPay, bKash merchant API, Firebase or Supabase).
- Reviews: add only real reviews, with the client's permission (RV in the script).
