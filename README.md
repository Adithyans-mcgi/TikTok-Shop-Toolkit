# 🛍 TikTok Shop Toolkit

A lightweight, single-file, client-side web application designed to streamline TikTok Shop operations, live flash sale scheduling, product ID mapping, and reference documentation.

## ✨ What's Inside

The application is split into three main tools housed in a single responsive interface:

1. **⚡ Flash Sale Generator**
   * Automatically calculates sequential 20-minute live flash sales with precise 1-second gaps.
   * Exports a custom-formatted Word document (`.docx`) complete with a scheduled preview table.

2. **💎 TikTok ID Mapper**
   * Reconciles internal product playbooks (`.xlsx` or `.csv`) with exported TikTok inventory sheets using SKU matching.
   * Automatically strips trailing size variants (e.g., matching `TT019-18` to `TT019`).
   * Fetches TikTok Product IDs or outputs tracking status text (*"Product already added"* vs *"need to add"*).
   * Pre-fills prices and generates a copy-pasteable box for unmatched SKUs.

3. **📘 Tutorials & Reference**
   * Built-in standard operating procedures for Seller Center, PIM workflows, restricted category rules, and shipping attributes.
   * Includes an interactive starting bid calculator ($Cost + \$10$) for JTV TikTok auctions.

---

## 🛠️ Technology Stack

* **Pure Vanilla HTML5, CSS3, and JavaScript** (No complex build tools or backend servers required).
* **[ExcelJS](https://github.com/exceljs/exceljs)** (Loaded via CDN) – Handles direct browser-side reading, manipulation, and exporting of Excel spreadsheets.
* **Custom ZIP & DOCX Generator** – Builds native Word documents directly in JavaScript using raw XML structures and local Blob objects.

---

## 🚀 Getting Started

Because this is a standalone client-side app, you don't need to install Node.js or configure a server:

1. Save your code file as `index.html`.
2. Double-click the file to open it directly in any modern web browser (Chrome, Edge, Firefox, Safari).

---

## 📄 License

This project is open-source and intended for internal team operations and workflow automation.
