# Cookie Crumblees Bakery Website - v6

A beautiful, mobile-responsive bakery website with shopping cart, map-based delivery, **automatic delivery fee calculation**, and WhatsApp ordering.

## 🌐 Live Website

Upload these files to your GitHub Pages repository in the `v6` folder:

- **Store:** `https://henawey.github.io/CookieCrumblees/v6/store.html`
- **Admin:** `https://henawey.github.io/CookieCrumblees/v6/admin.html`

## 📁 Required Files

Upload all these files to your GitHub repository:

```
v6/
├── store.html              (Customer-facing store)
├── admin.html              (Admin panel)
├── default-products.json   (Default products - REQUIRED!)
├── DEPLOYMENT-CHECKLIST.md
└── README.md              (This file)
```

## ⚠️ IMPORTANT: Default Products

The `default-products.json` file is **REQUIRED** and must be in the same folder as your HTML files!

- When users visit for the first time, they'll see sample products
- Admin can then customize, add, or remove products
- Without this file, store will be empty on first visit

## 🆕 What's New in v6

### 🚗 Delivery Fee System
- **Distance-based pricing**: Automatic calculation from your store location
- **Configurable pricing**: Set price per kilometer and base fee
- **Free delivery threshold**: Orders above specified amount get free delivery
- **Maximum delivery radius**: Set a maximum distance you'll deliver to
- **Real-time calculation**: Fee updates as customer selects location on map
- **Transparent pricing**: Customers see delivery fee before placing order

## 🗺️ Store Location

Your store location can be configured in the admin panel under **Delivery Fee Settings**.

**Default Location:**
District 9 - Orchid St - Al Barsha South Fifth - Jumeirah Village Triangle - Dubai
(Coordinates: 25.0478, 55.2011)

**To Change Your Store Location:**
1. Open admin panel
2. Go to "Delivery Fee Settings" → Click "Edit"
3. Update your store address and coordinates
4. Distance calculations will automatically use your new location

**How to Find Your Coordinates:**
1. Open Google Maps
2. Right-click on your store location
3. Click the coordinates to copy them
4. Paste into admin panel

Delivery distance is calculated from this location to the customer's selected address.

## 🔐 Admin Login

- **Username:** `admin`
- **Password:** `admin123`

## ✨ Features

- 🛒 Shopping cart with product management
- 🗺️ Interactive map for delivery address selection
- 🚗 **Automatic delivery fee calculation based on distance**
- 📱 WhatsApp order integration with full customer details
- 🎨 Beautiful, modern UI design
- 📦 Auto-generated product codes
- 💾 Export/Import data as JSON files
- ⚙️ Customizable store name and delivery settings
- 📍 Customer name, phone, address, and map location collection
- 🎉 Free delivery for orders above threshold

## 🚀 Quick Start

### GitHub Pages Setup:

1. Create a GitHub repository
2. Upload all files to a folder named `v6`
3. Enable GitHub Pages in Settings → Pages
4. Your site will be live with HTTPS!

## 📝 First Time Setup

1. Open `admin.html`
2. Login with default credentials
3. Update your **WhatsApp Number**: +971123456789 (or your number)
4. **Configure Delivery Settings:**
   - Price per kilometer (default: AED 2.00/km)
   - Base delivery fee (default: AED 5.00)
   - Minimum order for free delivery (default: AED 50.00)
   - Maximum delivery distance (default: 25 km)
5. Click **"Download Backup File"** to save your data
6. The default products will load automatically!

## 📱 Customer Order Details Sent via WhatsApp

When customer places order, you receive:
- Customer Name
- Customer Phone
- Delivery Address
- **Google Maps Link** to exact location (clickable!)
- **Distance from store in kilometers**
- Complete order list with prices
- **Delivery fee** (with calculation breakdown)
- **Total amount including delivery**

### Example WhatsApp Message:

```
🍪 New Order from Cookie Crumblees 🍪

Customer Information:
━━━━━━━━━━━━━━━━━━━━
👤 Name: Ahmed Henawey
📱 Phone: +971512345678

Delivery Information:
━━━━━━━━━━━━━━━━━━━━
🏠 Address: Claverton House 1, 36, Claverton Street...
📍 Location: https://www.google.com/maps?q=25.043,55.245
🚗 Distance: 3.45 km

Order Details:
━━━━━━━━━━━━━━━━━━━━

1. Cookie
   📦 Code: PRDMASS62
   ✖️ Quantity: 1
   💰 Price: AED 5.00
   💵 Subtotal: AED 5.00

2. Chocolate Brownie
   📦 Code: PRDXDYRZG
   ✖️ Quantity: 1
   💰 Price: AED 5.00
   💵 Subtotal: AED 5.00

━━━━━━━━━━━━━━━━━━━━
Subtotal: AED 10.00
Delivery Fee: AED 11.90
Total Amount: AED 21.90
```

## 🚗 Delivery Fee Calculation

The delivery fee is calculated as:
- **Base Fee** + (Distance × **Price Per Km**)
- Minimum charge is always the base fee
- If order total ≥ free delivery minimum → **FREE DELIVERY! 🎉**
- If distance > maximum radius → Customer cannot complete order

### Example Calculations:

**Scenario 1: Regular Order (5 km away, AED 20 order)**
- Distance: 5 km
- Base Fee: AED 5.00
- Distance Fee: 5 × AED 2.00 = AED 10.00
- **Total Delivery: AED 15.00**

**Scenario 2: Close Location (1 km away)**
- Distance: 1 km
- Base Fee: AED 5.00
- Distance Fee: 1 × AED 2.00 = AED 2.00
- **Total Delivery: AED 5.00** (base fee minimum)

**Scenario 3: Free Delivery (10 km away, AED 60 order)**
- Order Total: AED 60.00
- Free Delivery Threshold: AED 50.00
- **Delivery Fee: FREE! 🎉**

## 💾 Default Products Included

1. Delicious chocolate chips - AED 5
2. Chocolate Brownie - AED 5

## 🔧 Admin Panel Features

### Store Settings
- Store name and tagline
- WhatsApp number for orders
- Export/Import backup files

### Delivery Settings (NEW!)
- Configure price per kilometer
- Set base delivery fee
- Set minimum order for free delivery
- Set maximum delivery distance
- All settings update in real-time on store page

### Product Management
- Add/Edit/Delete products
- Upload product images
- Set categories and prices
- Auto-generated product codes
- View product statistics

---

Made with ❤️ for Cookie Crumblees
