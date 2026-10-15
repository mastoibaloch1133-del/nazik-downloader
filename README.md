# GNT Downloader

<div align="center">

**A modern, fast, and privacy-focused social media video downloader.**

Download HD videos from TikTok, YouTube, Instagram, Facebook, Twitter/X, Snapchat, Pinterest and 20+ platforms — free, no signup, no watermark.

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge&logo=cloudflare)](https://gnt-downloader.pages.dev)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)]()

</div>

---

## 📖 About

**GNT Downloader** is a lightweight, browser-based tool that lets anyone download videos and audio from major social media platforms in the highest available quality. Built with pure HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies.

The project is designed with **speed**, **privacy**, and **simplicity** at its core: no accounts, no tracking, no ads, and no watermarks.

---

## ✨ Features

- 🚀 **Lightning Fast** — Parses and delivers media in seconds
- 🎬 **HD & 4K Support** — Downloads in the highest quality available
- 🔒 **100% Private** — No accounts, no tracking, no data stored
- 💧 **No Watermark** — Clean, watermark-free downloads
- 📱 **Fully Responsive** — Works on phone, tablet, laptop, and desktop
- ♾️ **Unlimited Downloads** — No daily limits, no hidden caps
- 🌗 **Dark & Light Theme** — Auto-detects system preference
- 📜 **Recent Downloads** — Re-download previously saved files
- 🎯 **20+ Platforms** — TikTok, YouTube, Instagram, Facebook, Twitter/X, Snapchat, Pinterest, and more
- 💸 **Completely Free** — No premium tier, no paywall

---

## 🌐 Supported Platforms

| Platform | Status | Notes |
|----------|:------:|-------|
| TikTok | ✅ | No watermark |
| YouTube | ✅ | Multiple qualities (up to 4K) |
| Instagram | ✅ | Reels, Posts, IGTV |
| Facebook | ✅ | Public videos |
| Twitter / X | ✅ | All public videos |
| Snapchat | ✅ | Public stories |
| Pinterest | ✅ | Video pins |
| LinkedIn | ✅ | Public videos |
| Reddit | ✅ | v.redd.it links |
| Vimeo | ✅ | Public videos |
| Dailymotion | ✅ | Public videos |
| And 10+ more | ✅ | Continuously expanding |

> **Note:** Only publicly available content can be downloaded. Private, age-restricted, or protected videos are not supported.

---

## 🚀 Quick Start

### Option 1: Use the Live Site

Just visit **[gnt-downloader.pages.dev](https://gnt-downloader.pages.dev)** — nothing to install.

### Option 2: Run Locally

No build step is needed. Download or clone the project, then either open `index.html` in a browser or serve the folder with any static server:

```bash
python3 -m http.server 8000
# Then visit http://localhost:8000
```

---

## 📁 Project Structure

| File | Purpose |
|------|---------|
| `index.html` | Main downloader page (HTML, CSS, JS in one file) |
| `about/`, `privacy/`, `terms/` | Info and legal pages |
| `404.html` | Not-found page (served automatically by Cloudflare Pages) |
| `sitemap.xml`, `robots.txt` | Search engine files |
| `_headers` | Cloudflare Pages response headers |
| `favicon.svg`, `apple-touch-icon.png`, `og-image.png` | Icons and social preview image |

---

## 🔎 Google Search Console

1. Deploy to Cloudflare Pages.
2. In Search Console, submit `https://gnt-downloader.pages.dev/sitemap.xml`.
3. Use URL Inspection → **Request Indexing** for each page.

---

## 📄 License

Released under the [MIT License](LICENSE).
