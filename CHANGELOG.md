# Changelog

All notable user-facing changes to the **PharmaBill** desktop application, platform, and binary distributions are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.2] - 2026-10-30

### 🚀 Added
- **Interactive Help & Knowledge Center**: Integrated high-intent pharmacy FAQ knowledge base with clear definitions covering inventory workflows, billing shortcuts, and GST compliance.
- **Search & Discovery Enhancements**: Implemented rich structured data and enhanced web metadata for improved visibility across search engines and AI assistants.
- **Modern Asset Delivery**: Optimized application image assets with next-generation WebP delivery for faster page and asset loading.
- **Accessibility Improvements**: Added keyboard-friendly skip navigation for improved accessibility.

### 🔄 Changed
- **Content Hierarchy Normalization**: Streamlined documentation and landing page structure for improved navigation and reading clarity.
- **Counter Workflow Highlights**: Refined feature presentations to better showcase keyboard-first billing and batch expiry management.

### ⚡ Performance & Polish
- Reduced application bundle size by removing unused legacy graphic assets.
- General performance optimizations across desktop application views.

---

## [1.0.1] - 2026-10-29

### 🚀 Added
- **Offline Counter Billing Resilience**: Enhanced offline mode allowing continuous invoice generation and receipt printing during network interruptions.
- **Automatic Background Synchronization**: Real-time background sync that reconciles sales records and inventory adjustments when connectivity resumes.
- **Thermal Receipt Printer Support**: Plug-and-play USB interface for standard 3-inch ESC/POS thermal receipt printers.
- **Barcode Scanner Compatibility**: Instant product lookup via standard USB barcode scanners.

### 🛠️ Improvements & Fixes
- Enhanced desktop application launch stability on Windows and Linux systems.
- Optimized Linux package setup and installation compatibility for modern distributions.

---

## [1.0.0] - 2026-10-29

### 🚀 Added
- **Initial Production Release**: Official production desktop application release for Windows (`.exe`), Ubuntu/Debian (`.deb`), and Linux (`.AppImage`).
- **Keyboard-First Billing Engine**: Fast POS counter checkout operating completely via hotkeys and barcode input.
- **Automated FEFO Batch Tracking**: Automatic First-Expiry-First-Out medicine dispensing to prevent expired stock accumulation.
- **GST-Ready Invoicing**: Automated CGST, SGST, and IGST tax calculation with itemized HSN codes and receipt printing.
- **Multi-Branch Operations**: Centralized purchase orders, inter-branch stock transfers, and branch-level ledger tracking.
- **Staff Access Controls**: Configurable staff roles and counter permissions for administrative and billing staff.
- **Package Integrity Verification**: Cryptographic SHA256 verification checksums for all official release packages.

---

[1.0.2]: https://github.com/Mr-Bhardwa7/PharmaBill/releases/tag/v1.0.2
[1.0.1]: https://github.com/Mr-Bhardwa7/PharmaBill/releases/tag/v1.0.1
[1.0.0]: https://github.com/Mr-Bhardwa7/PharmaBill/releases/tag/v1.0.0
