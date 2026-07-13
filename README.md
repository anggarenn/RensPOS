# 🚀 RensPOS - Advanced F&B Point of Sales System 

RensPOS is a highly optimized, dual-application Point of Sales (POS) ecosystem built specifically for Food & Beverage businesses. Engineered with a true **offline-first** architecture and hardware-accelerated rendering, RensPOS delivers a buttery-smooth 60fps experience even on lower-end Android devices.

## ✨ Core Highlights

- **Offline-First Synchronization**: Continues to operate flawlessly without internet. Data is cached locally using Zustand Persist and syncs automatically with the cloud upon reconnection.
- **Dual-App Ecosystem**:
  - 📱 **POS App**: The main cashier application featuring a Kitchen Display System (KDS), intelligent cart logic, ingredient-level inventory, and a dynamic media gallery.
  - 💻 **Admin Panel**: A centralized web dashboard for generating exclusive license keys, managing activations, and monitoring registered merchants.
- **Smart Ingredient Conversions**: Built-in raw material management with automatic metric conversions (e.g., Karton → Pack → Gram), specifically tailored for complex F&B recipe calculations.
- **Anti-Tearing Rendering Engine**: Customized Android WebView optimizations to prevent layout tearing and ghosting, ensuring ultra-smooth scrolling on intensive modal lists.

## 🛠️ Technology Stack

- **Frontend Core**: React 18, TypeScript, Vite
- **Mobile Capabilities**: Capacitor v6 for native Android/iOS bridging
- **State Management**: Zustand (Global Store + LocalStorage Persistence)
- **Styling Engine**: Tailwind CSS v4 + Headless UI concepts for maximum customization
- **Backend Architecture**: Supabase (PostgreSQL, Row Level Security, Realtime Sync)
- **UI Assets**: Tabler Icons React

## 📦 Repository Structure

This repository acts as a mono-repo showcasing the compiled assets and documentation.

```text
📦 RensPOS
 ┣ 📂 releases/
 ┃ ┗ 📜 RensPOS-v1.0.apk  <-- Download the compiled Android App here!
 ┗ 📜 README.md
```

## 📥 Direct Download

Experience the app directly on your Android device!
🔗 **[Download RensPOS v1.0 APK](./releases/RensPOS-v1.0.apk)**

## 📸 Application Preview
*(Place your application screenshots here to showcase the beautiful UI!)*

---
*Developed by **Anggaren** - Built with ❤️ for modern F&B businesses.*
