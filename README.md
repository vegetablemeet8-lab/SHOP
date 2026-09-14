# Book Shop Professional v2

This version is a much fuller functional prototype for a single book shop.

## What is included
- Professional admin login/dashboard
- Books/products CRUD
- Barcode/ISBN field
- Phone/USB/Bluetooth scanner keyboard-style input
- Billing/POS
- Customers
- Stock and low-stock alerts
- Expenses
- Sales/profit report cards
- Website preview
- Settings
- Local browser data persistence
- Responsive mobile/PC layout
- Python desktop launcher

## Demo login
Username: admin
Password: admin123

## Run
Double-click `desktop_app/app.py` if Python is associated with .py files, or run:
`python desktop_app/app.py`

You can also open `website/index.html` directly.

## Important
This is a working prototype, not yet a production multi-user/cloud system. The next production stage should replace localStorage with SQLite/PostgreSQL/API, add secure authentication, real invoice printing/PDF, camera barcode support where available, backups, and website-to-desktop synchronization.
