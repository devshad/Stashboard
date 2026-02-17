# 🛡️ StashBoard
> **Your Private, Offline-First Digital Vault.**

StashBoard is a modern, secure, and beautiful application for managing your digital life. Whether it's passwords, important files, personal notes, or image collections, StashBoard keeps everything organized and encrypted right on your device.

## 🚀 Why Choose StashBoard?

In an era of cloud breaches and data tracking, StashBoard takes a **privacy-first** approach:

- **100% Local**: Your data never leaves your computer. No cloud servers, no subscriptions, no tracking.
- **Military-Grade Security**: Sensitive data (like passwords) is encrypted using **AES-256-GCM**.
- **Data Sovereignty**: You decide where your vault lives. Move it to a USB drive, a secure folder, or back it up manually.
- **Blazing Fast**: Built with **Rust** and **Tauri**, it uses a fraction of the RAM of Electron apps.

## ✨ Key Features

### 🔐 Secure Password Manager
- **Built-in Encryption**: Passwords are encrypted at rest.
- **Generator**: Create strong, unique passwords with a click.
- **Strength Meter**: Visual feedback on password complexity.
- **Privacy Mode**: Hidden by default, revealed only when you need them.

### 📂 Digital File Vault
- **Drag & Drop**: Simply drag files onto the dashboard to secure them.
- **Physical Organization**: Files are sorted into `images/`, `videos/`, and `documents/` inside your vault.
- **Smart Attachments**: Attach reference files to any item (e.g., a receipt attached to a purchase record).

### 🖼️ Visual Gallery
- **Dedicated Image Support**: A stunning gallery layout for your image collections.
- **Large Previews**: 220px+ tall previews for easy browsing.
- **Overlay Actions**: Edit, pin, or delete images directly from the card.

### 🎥 Video & Media Support
-   **Native Playback**: Watch videos directly within the app.
-   **Gallery View**: Dedicated layouts for Images and Videos.
-   **Show in Folder**: Click the 📂 icon to instantly locate any file in Explorer.

### 🧠 Smart Organization
-   **Categories & Labels**: Color-coded tags and custom categories.
-   **Context-Aware Search**: Search respects your current view (e.g., searching while in "Work" only shows Work items).
-   **Strict Favorites**: Filter search results to only show your favorite items.
-   **Global Search**: Instantly find anything by title, content, or tag.

### 🛡️ Advanced Security
-   **Auto-Lock**: Automatically locks the vault after 5 minutes (configurable) of inactivity.
-   **Master Password**: Your single key to decrypt the vault. We don't know it, so don't lose it!
-   **Recovery Codes**: Generate emergency codes to regain access if you forget your password.
-   **Secure File Naming**: Files are automatically renamed (`_SBcpX`) to prevent overwrites while preserving original names.

## 🛠️ Tech Stack

StashBoard is built on a modern, high-performance stack:
- **Core**: [Rust](https://www.rust-lang.org/) (Tauri Framework)
- **Frontend**: React + Vite
- **Database**: SQLite (SQLCipher-ready architecture)
- **Styling**: Modern CSS with Glassmorphism & Dark Mode

## 🏁 Getting Started

### Prerequisites
- Node.js (v18+)
- Rust (stable)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stashboard.git
   cd stashboard
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run in Development Mode:
   ```bash
   npm run tauri dev
   ```

4. Build for Production:
   ```bash
   npm run tauri build
   ```

---
*StashBoard — Reclaim your digital privacy.*
