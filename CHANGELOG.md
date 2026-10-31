# PharmaBill — What's New

Welcome to the **PharmaBill** release notes! This page lists all new features, improvements, and fixes in everyday, easy-to-understand language so you and your pharmacy staff know exactly what's new.

---

## Version 1.0.2 (October 30, 2026)

### 🌟 New Features & Everyday Improvements

* **In-App Update Notification Button**:
  * Whenever a newer version of PharmaBill is available, an **[Update]** pill button will now appear at the top of your screen so you can update right away.
  * Your current software version is also clearly displayed at the bottom of the left sidebar menu for easy reference.

* **Screen Zoom In & Zoom Out Controls**:
  * You can now easily make the screen text larger or smaller to suit your monitor using the new **+** and **-** zoom buttons in the titlebar, or by pressing **Ctrl and +** / **Ctrl and -** on your keyboard. Press **Ctrl and 0** to reset back to normal (100%).
  * The top window buttons stay fixed and sharp regardless of your zoom level.
  * Your preferred zoom setting is automatically remembered the next time you open the app.

* **New Interactive Pharmacy FAQ Guide**:
  * Added a dedicated help and questions section on our website explaining counter shortcuts, batch tracking, and Indian GST billing rules.

* **Faster Page & Asset Loading**:
  * Upgraded application graphics and icons for noticeably faster page opening and lower data usage.

---

### 🛠️ Fixes & Counter Stability

* **Smoother Payment Counter Popup**:
  * Fixed an issue where the payment dialog popup in the billing counter could freeze or take extra clicks to complete payment during busy checkout hours.

* **Decimal Prices for Purchases & Stock**:
  * You can now enter prices with paise/decimal points (e.g., ₹14.50) when recording supplier purchases and adding new medicine stocks.

* **Supplier Purchase Order Saving**:
  * Fixed an issue that previously prevented new supplier purchase orders from saving and submitting properly.

* **Cleaner Activity History (Audit Logs)**:
  * When reviewing past activity logs, you will now see only the exact items that were changed rather than long, unchanged form lists.

---

## Version 1.0.1 (October 29, 2026)

### 🌟 New Features & Everyday Improvements

* **Offline Counter Billing Resilience**:
  * Keep billing customers and issuing receipts without interruption even if your internet connection drops.
  * All offline bills and stock adjustments automatically sync to the cloud the moment your internet reconnects.

* **Receipt Printer & Barcode Scanner Plug-and-Play**:
  * Direct plug-and-play support for standard 3-inch thermal receipt printers (no complex printer drivers needed).
  * Instant medicine lookup by scanning product barcodes with your USB barcode scanner.

---

### 🛠️ Fixes & Stability

* **Navigation Menu Highlighting**:
  * Fixed menu tabs to clearly highlight the page you are currently viewing.

* **Supplier Cards on Smaller Screens**:
  * Adjusted supplier cards so text and buttons fit cleanly without cutoffs on smaller counter monitors.

* **Flexible Supplier Details**:
  * Supplier contact phone and email fields are now optional, letting you quickly save local distributors with minimal typing.

* **Desktop App Startup Stability**:
  * Improved overall launch speed and window stability on Windows and Linux computers.

---

## Version 1.0.0 (October 29, 2026)

### 🚀 Initial Production Release

* **First Official Release of PharmaBill**:
  * Official desktop application launch for Windows (10 and 11) and Ubuntu / Debian Linux computers.

* **Keyboard-First Fast Counter Billing**:
  * Complete customer bills without reaching for a mouse:
    * Press **`/`** to instantly search medicines.
    * Press **`C`** to select or add a customer.
    * Press **`PP`** to open the quick payment dialog.
    * Press **`Enter`** to auto-select the nearest-expiry batch.

* **Automatic FEFO (First-Expiry-First-Out) Batch Tracking**:
  * The system automatically selects the batch expiring earliest so you never accidentally sell older stock or incur expired medicine losses.

* **GST-Ready Tax Invoicing**:
  * Automatic calculation of CGST, SGST, and IGST with required HSN codes and printed tax receipts.

* **Multi-Branch Pharmacy Management**:
  * Central purchase orders, inter-branch stock transfers, and branch-level ledger tracking from a single dashboard.

* **Staff Permissions & Accounts**:
  * Separate login accounts with customizable counter permissions for Cashiers, Pharmacists, Managers, and Store Admins.
