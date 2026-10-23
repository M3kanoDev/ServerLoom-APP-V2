# Changelog

Public release notes for **ServerLoom App**, the platform behind [serverloom.com](https://serverloom.com), crafted by [iLoomX](https://iloomx.com).

## 2.0 - 2026-10-23 🚀

**ServerLoom App v2 is a complete rebuild** on Laravel 13 · PHP 8.5 · Filament 5 · Livewire 4 · Tailwind CSS 4.
Every customer account, service and wallet balance moved over unchanged.

### ✨ New
- **Passkey sign-in** for customers and staff: Face ID, Touch ID or Windows Hello, no password
- **Redesigned sign-in**: one screen, one-click Google / GitHub / Discord, and a welcome animation
- **Redesigned password recovery**
- **System health** monitoring, with instant Telegram / Discord alerts when anything fails
- **Activity log**: a full audit trail of staff actions
- **Notification centre**, with direct messages to customers
- **Ctrl+K spotlight search** and saved table views in the staff console
- **Provider management** in the UI, with credentials stored encrypted
- **Multiple reverse-DNS domains**: customers pick their hostname domain
- **Branded emails** across the whole platform

### ⚡ Faster
- Self-hosted fonts and a trimmed icon set (302 KB → 32 KB)
- No render-blocking third-party scripts
- Lighter, phone-first pages for the storefront and the customer panel

### 🛡️ Safer
- Hardened checkout and payment paths
- Tamper-proof panel state
- Strict security headers, with credentials encrypted at rest
- Bot protection on every public form

### 🔧 Smoother
- Web hosting goes live in seconds, and free subdomains get their DNS record automatically
- "Access cPanel" opens in a new tab
- Backups run in the background and are monitored
- Clearer status for slow provider operations

---

## 1.x

The original ServerLoom platform, now retired in favour of v2.
