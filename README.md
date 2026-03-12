# 🎵 221st Street Music: Catalog Manager’s Guide

Welcome to your music catalog! This site is designed to be high-performance, mobile-friendly, and easy to update without needing to write complex code.

---

## 📂 What’s in this Folder?

| File/Folder | What it does |
| :--- | :--- |
| index.html | The Engine. The actual website code. You usually won't need to touch this. |
| songs.json | The Database. This is where you add song titles, writers, and lyrics. |
| audio/ | The Vault. This folder is where you upload your .mp3 files. |
| logo.png | The Brand. Your optimized logo used in the header and footer. |

---

## 🏠 Navigation Features

We have added two ways for users to get back to your main site (221street.com):

1. **The "< Home" Link:** Located at the top left of the header.
2. **Clickable Logos:** Both the top header logo and the bottom footer logo now act as direct links back to your homepage.

---

## 🛠 How to Add a New Song

Updating the site is a simple 3-step process. 

### Step 1: Upload the Audio
* Drop your song file (e.g., `Sleigh_Ride.mp3`) into the **audio** folder.
* **Crucial:** Make sure the filename has no spaces and ends in `.mp3`.

### Step 2: Update the JSON Database
Open `songs.json` in a text editor. To add a new song, copy a previous "block" of code and change the details.

**The Comma Rule:** Every song block needs a comma after the `}` except for the **very last song** in the list.

**The File Name:** The `file` entry must match your MP3 filename in the audio folder *exactly*.

### Step 3: Save and Sync
1. Save your changes to `songs.json`.
2. Open **GitHub Desktop**.
3. Type a summary (e.g., "Added New Hit") in the bottom left.
4. Click **Commit to main** then **Push origin**.

---

## ⚠️ Troubleshooting "The Oopsies"

* **"The site is totally blank!"** Check for a missing comma or quote in `songs.json`.

* **"The song won't play!"** Make sure the `file` name in JSON matches the `.mp3` file exactly.

* **"The lyrics are all on one line!"** Use `\n` where you want a new line to start (e.g., `Verse 1:\nThis is line two`).

---

## 🔒 Built-in Protection
* **Right-Click Disabled:** Prevents easy "Save As" on your assets.
* **Watermarking:** A "PROPRIETARY" watermark is automatically placed over all lyrics.
* **Legal Footer:** International copyright notices are locked at the bottom.

---

**Developed with ❤️ by Victor Perez**
