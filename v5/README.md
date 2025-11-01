# Cookies Crumblees Bakery Website

A beautiful, mobile-responsive bakery website with shopping cart, map-based delivery, and WhatsApp ordering.

## 🌐 Live Website

Upload these files to your GitHub Pages repository in the `v4` folder:

- **Store:** `https://henawey.github.io/CookieCrumblees/v5/store.html`
- **Admin:** `https://henawey.github.io/CookieCrumblees/v5/admin.html`

## 📁 Required Files

Upload all these files to your GitHub repository:

```
v4/
├── store.html              (Customer-facing store)
├── admin.html              (Admin panel)
├── default-products.json   (Default products - REQUIRED!)
├── sample-data.json        (Sample backup file)
└── README.md              (This file)
```

## ⚠️ IMPORTANT: Default Products

The `default-products.json` file is **REQUIRED** and must be in the same folder as your HTML files!

- When users visit for the first time, they'll see 2 sample products
- Admin can then customize, add, or remove products
- Without this file, store will be empty on first visit

## 🗺️ Map Location

The map is currently set to **Dubai, UAE** coordinates (your location):
- Latitude: 25.2048
- Longitude: 55.2708

This is correct for Dubai! The map will center on Dubai by default.

## 🔐 Admin Login

- **Username:** `admin`
- **Password:** `admin123`

## ✨ Features

- 🛒 Shopping cart with product management
- 🗺️ Interactive map for delivery address selection (Dubai default)
- 📱 WhatsApp order integration with full customer details
- 🎨 Beautiful, modern UI design
- 📦 Auto-generated product codes
- 💾 Export/Import data as JSON files
- ⚙️ Customizable store name and settings
- 📍 Customer name, phone, address, and map location collection

## 🚀 Quick Start

### GitHub Pages Setup:

1. Create a GitHub repository
2. Upload all files to a folder named `v5`
3. Enable GitHub Pages in Settings → Pages
4. Your site will be live with HTTPS!

## 📝 First Time Setup

1. Open `admin.html`
2. Login with default credentials
3. Update your WhatsApp Number: **+971123456789** (or your number)
4. Click **"Download Backup File"** to save your data
5. The default products will load automatically!

## 📱 Customer Order Details Sent via WhatsApp

When customer places order, you receive:
- Customer Name
- Customer Phone
- Delivery Address
- **Google Maps Link** to exact location (clickable!)
- Complete order list with prices
- Total amount

## 💾 Default Products Included

1. Delicious chocolate chips - AED 5
2. Chocolate Brownie - AED 5

---

Made with ❤️ for Cookie Crumblees
