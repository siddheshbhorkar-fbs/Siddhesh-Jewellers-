# eidddhesh 01 — Siddhesh Jewellers

A responsive jewellery-shop dashboard starter for shop overview, ornament inventory, customer records, staff access and A4 billing.

## Run locally

1. Install [Node.js](https://nodejs.org/) (18 or newer).
2. In this project folder, run `npm install`.
3. Run `npm run dev` and open the local URL printed by Vite.
4. Create a production build with `npm run build`.

## Included

- Owner dashboard with sales snapshot, recent transactions and featured ornaments.
- Gold, silver and diamond inventory with search, category filters, stock editing and add-item forms.
- Customer book and local staff roster with role/permission labels.
- Cart-based billing with discount, GST, payment method and A4 invoice print layout.
- Shop profile, logo upload, invoice prefix and configurable shop metal rates.
- Customer-facing display screen for in-store rates.
- Browser-local persistence using `localStorage`.

## Important setup notes

- The sample rates and products are starter/demo data. The metal rates are **manual shop-entered reference rates**, not a connected live market feed. Enter rates from your trusted provider under **Shop settings → Shop metal rates** before issuing bills. A real feed requires a market-data provider, API credentials and a backend integration.
- The browser uses its system print dialog for invoices. Select a paired Bluetooth printer or connected wired printer that supports A4 paper. Bluetooth printer support depends on the browser, operating system and printer; the app does not directly pair or manage printers.
- Owner/staff records and shop data in this starter are kept only in the current browser. This is a front-end prototype, not secure multi-user authentication or cloud storage. Before using for real business, connect a backend, secure staff accounts and permissions, configure GST/legal invoice details and take backups.
- Product imagery is loaded from Unsplash and requires an internet connection. Replace sample images with your own licensed jewellery photographs for production use.
