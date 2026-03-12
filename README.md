# 🎵 221st Street Music: Catalog Manager’s Guide

Welcome to your music catalog! This site is designed to be high-performance, mobile-friendly, and easy to update without needing to write complex code.

---

## 📂 What’s in this Folder?

| File/Folder | What it does |
| :--- | :--- |
| **index.html** | **The Engine.** This is the actual website code. You usually won't need to touch this. |
| **songs.json** | **The Database.** This is where you add song titles, writers, and lyrics. |
| **audio/** | **The Vault.** This folder is where you upload your .mp3 files. |
| **logo.png** | **The Brand.** Your optimized logo used in the header and footer. |

---

## 🛠 How to Add a New Song

Updating the site is a simple 3-step process. 

### **Step 1: Upload the Audio**
1. Take your song file (e.g., `Sleigh_Ride.mp3`).
2. Drop it into the `audio` folder.
3. **Crucial:** Make sure the filename has no spaces and ends in `.mp3`.

### **Step 2: Update the JSON Database**
Open `songs.json` in a text editor. To add a new song, copy a previous "block" of code and change the details.

**Example of a song block:**
```json
{
  "id": "track-08",
  "title": "Your New Hit",
  "writers": ["Kenny WayDownLow", "The Atelier"],
  "genre": "K-Pop",
  "file": "your_filename.mp3",
  "lyrics": "Verse 1:\nLyrics go here...",
  "tags": ["Upbeat", "Retro"]
}

The Comma Rule: Every song block needs a comma after the } except for the very last song in the list.

The File Name: The file entry must match your MP3 filename in the audio folder exactly.

Step 3: Save and Sync
Save your changes to songs.json.

Open GitHub Desktop.

Type a summary (e.g., "Added New Hit") in the bottom left.

Click Commit to main then Push origin.

⚠️ Troubleshooting "The Oopsies"
"The site is totally blank!" * Check for a missing comma or quote in songs.json.

"The song won't play!" * Make sure the file name in JSON matches the .mp3 file exactly.

"The lyrics are all on one line!" * Use \n where you want a new line to start.

🔒 Built-in Protection
Right-Click Disabled: Prevents easy "Save As" on your assets.

Watermarking: A "PROPRIETARY" watermark is automatically placed over all lyrics.

Legal Footer: International copyright notices are locked at the bottom.

Developed with ❤️ by Victor Perez
