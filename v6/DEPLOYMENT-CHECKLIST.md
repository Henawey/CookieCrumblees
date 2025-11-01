# 🚀 DEPLOYMENT CHECKLIST - v6

## ✅ Files to Upload to GitHub (in v6 folder)

1. ☐ store.html
2. ☐ admin.html  
3. ☐ default-products.json ⚠️ REQUIRED!
4. ☐ README.md
5. ☐ DEPLOYMENT-CHECKLIST.md (this file)

## 📍 Your Settings

**Store Location:** Configurable in admin panel (default: JVT, Dubai)

**Store Name:** Cookie Crumblees (or change in admin)

**WhatsApp:** +971123456789 (update in admin settings)

## 🆕 New in v6: Delivery Fee System

### Default Delivery Settings
- ✅ **Store Location:** Editable in admin (default: JVT, Dubai)
- ✅ **Price per km:** AED 2.00/km
- ✅ **Base fee:** AED 5.00 (minimum charge)
- ✅ **Free delivery at:** AED 50.00+ orders
- ✅ **Max distance:** 25 km from store

### How It Works
1. Customer selects location on map
2. System calculates distance from your store (JVT)
3. Delivery fee automatically calculated and displayed
4. Fee included in WhatsApp order message
5. Orders above AED 50 get FREE delivery! 🎉

## 🔧 What's Fixed & Improved

✅ **Delivery Fee Calculation** - Automatic distance-based pricing
✅ **Real-time Updates** - Fee updates as customer selects location
✅ **Free Delivery** - Configurable minimum order threshold
✅ **Distance Limits** - Set maximum delivery radius
✅ **Transparent Pricing** - Customers see all costs before ordering
✅ **Map Location** - Set to Dubai, UAE (your location)
✅ **Default Products** - 2 products load automatically on first visit
✅ **WhatsApp Integration** - Includes delivery distance and fee

## 📱 WhatsApp Message Now Includes

When customer orders, you get:
- ✅ Customer name
- ✅ Customer phone (with + prefix)
- ✅ Delivery address
- ✅ **Google Maps link** (clickable location!)
- ✅ **Distance from store** (in km)
- ✅ Full order details
- ✅ **Delivery fee breakdown**
- ✅ Subtotal + Delivery = **Total amount**

## 🎯 Next Steps

1. Upload all files to GitHub in `v6` folder
2. Enable GitHub Pages
3. Open admin.html 
4. Login with: **admin** / **admin123**
5. Update WhatsApp number to: **+971123456789**
6. **Configure Delivery Settings:**
   - Go to "Delivery Fee Settings" section
   - Click "Edit" button
   - Set your **Store Location** (address and coordinates)
   - Adjust pricing to your preferences
   - Set free delivery minimum
   - Set maximum delivery distance
7. Customize products as needed
8. Download a backup file
9. Share store link with customers!

## 🌐 Your URLs will be:

```
Store: https://henawey.github.io/CookieCrumblees/v6/store.html
Admin: https://henawey.github.io/CookieCrumblees/v6/admin.html
```

## ⚙️ Admin Panel - Delivery Settings

To configure delivery fees:

1. Open admin panel
2. Scroll to **"Delivery Fee Settings"** section
3. Click **"Edit"** button
4. Configure:
   - **Store Location**: 
     - Store address (for reference)
     - Latitude and Longitude (for distance calculation)
     - 💡 Use Google Maps to find your coordinates
   - **Price Per Kilometer**: How much to charge per km (e.g., AED 2.00)
   - **Base Delivery Fee**: Minimum charge regardless of distance (e.g., AED 5.00)
   - **Free Delivery Minimum**: Order amount for free delivery (e.g., AED 50.00, or 0 to disable)
   - **Maximum Delivery Distance**: Farthest you'll deliver in km (e.g., 25 km, or 0 for unlimited)
5. Click **"Save Settings"**

Changes apply immediately to the store page!

## 🚗 Delivery Fee Examples

Based on default settings (AED 2.00/km, AED 5.00 base, AED 50+ free):

| Distance | Order Amount | Calculation | Delivery Fee |
|----------|--------------|-------------|--------------|
| 2 km | AED 20 | Base fee (min) | **AED 5.00** |
| 5 km | AED 30 | 5.00 + (5 × 2.00) | **AED 15.00** |
| 10 km | AED 40 | 5.00 + (10 × 2.00) | **AED 25.00** |
| 10 km | **AED 60** | Free delivery! | **FREE 🎉** |
| 30 km | AED 100 | Beyond max (25km) | **❌ Cannot deliver** |

## ⚠️ CRITICAL

**default-products.json MUST be uploaded** or store will be empty!

---

## 🎉 Benefits of v6 Delivery System

✨ **For You:**
- Automatic fair pricing based on distance
- Control over delivery zones
- Encourage larger orders with free delivery
- Reduced manual calculations
- Professional customer experience

✨ **For Customers:**
- See delivery cost before ordering
- Transparent pricing
- Motivation to reach free delivery threshold
- Know if they're in delivery area
- Better ordering experience

---

You're all set! 🎉 Happy selling! 🍪
