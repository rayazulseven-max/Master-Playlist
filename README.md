# 221st Street Music - Searchable Catalog v1.0

A high-performance, standalone web application built for **221st Street Publishing**. This catalog features a dynamic search system, integrated media player, and proprietary IP protection.

## 🚀 Live Demo
View the production site here: [https://rayazulseven-max.github.io/Master-Playlist/](https://rayazulseven-max.github.io/Master-Playlist/)

## ✨ Key Features
* **Dynamic Data Fetching:** Utilizes a centralized JSON database for effortless catalog management.
* **Sticky UI Framework:** Features a fixed brand header and a sticky desktop sidebar to keep player controls and lyrics in view at all times.
* **Mobile-Optimized:** Fully responsive design that swaps to a top-pinned mobile player for on-the-go access.
* **IP Protection:** Integrated right-click disabling and dynamic watermarking on lyrics to protect creative assets.
* **Custom Branding:** High-end "Dark Mode" aesthetic with a bespoke sticky footer and overlapping logo design.

## 📁 File Structure & Purpose

| File/Folder | Purpose |
| :--- | :--- |
| `index.html` | The core application (Structure, CSS, and JavaScript logic). |
| `songs.json` | The database containing all track metadata and lyrics. |
| `logo.png` | Optimized brand asset (600x246px). |
| `/audio/` | Directory for all hosted MP3 assets. |



## 🛠 Maintenance Guide
To add new music to the catalog:

1.  **Add Audio:** Place the `.mp3` file into the `/audio/` folder.
2.  **Update Database:** Add a new entry to `songs.json`.
    > **Note:** Ensure the `"file"` name in the JSON matches your MP3 filename exactly.
3.  **Deploy:** Commit and Push via GitHub Desktop.

## 🛡 Intellectual Property
All compositions and brand assets are the intellectual property of **221st Street Music LLC**. No part of these compositions may be used in any form without expressed written permission.

---
*Developed by Victor Perez in collaboration with Gemini.*
