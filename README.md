<img width="1408" height="768" alt="DelphiTrack" src="https://github.com/user-attachments/assets/f408ad1e-e14a-44b4-9d01-e6b84efc24b1" />
# DelphiTrack

> **Precision inventory. Instant clarity.**

DelphiTrack is a sleek, high-precision stock-taking, calculation, and store auditing application built for **Delphia**. Designed for shop floor managers and audit teams, it eliminates inventory friction with automated stock deductions, receipt tracking, visual product audits, customer credit tracking, and seamless **offline-first mobile and web synchronization**.

---

## 🛠️ Technology Stack

DelphiTrack is built as a unified cross-platform application (Web & Mobile) with robust offline functionality:

* **Frontend / Mobile:** Flutter (Dart) / React Native (TypeScript) – *Cross-platform Web, iOS, and Android*
* **Local Offline Database:** SQLite / Hive – *Enables full offline operations on mobile devices*
* **Backend & Storage:** Supabase / Firebase – *Real-time database sync, cloud authentication, and image storage*

---

## 🌟 Key Features

* **🧮 Live Inventory Calculator:** Deducts products directly from available stock levels in real time as sales or counts are calculated.
* **📲 Cross-Platform & Offline Support:** Operates seamlessly on mobile devices without an active internet connection; automatically syncs data when connected.
* **🏷️ Dual-Pricing & Supplier Directory:** 
  * Maintains a complete catalog of suppliers.
  * Tracks both supplier cost prices and Delphia retail prices side-by-side.
* **🧾 Receipt & Document Archiving:** Capture and store image proofs of receipts for stock paid for and received from suppliers.
* **📸 Visual Product Audits:** 
  * Take photos of products sold directly on the shop floor.
  * Instant access to detailed product profiles including **Supplier Name**, **Supplier Price**, **Delphia Shop Price**, and **Expected Profit Margin**.
* **📊 Comprehensive Auditing:** Automatically reconciles live counts, wholesale costs, shop prices, and projected profit margins.
* **📖 Dinau / Customer Credit Tracker:** Dedicated ledger section to log, track, and audit customers buying on store credit (*dinau*).

---

## 🎨 Brand Identity

* **Colors:** Deep Blue (`#0F2942`) & Crimson Red (`#C8102E`)
* **Tone:** Professional, fast, data-driven, and utility-focused.

---

## 🚀 Quick Start

### Prerequisites

* [Flutter SDK](https://docs.flutter.dev/get-started/install) (v3.0+) or Node.js (v18.0+)
* Mobile device emulator (Android Studio / Xcode) or modern Web Browser

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Delphia/DelphiTrack.git](https://github.com/Delphia/DelphiTrack.git)
   cd DelphiTrack
