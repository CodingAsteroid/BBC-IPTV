# 📺 BBC-IPTV

**A streamlined, HD playlist of all BBC channels, optimized for seamless EPG integration.**

## 📖 Overview

BBC-IPTV is a curated M3U playlist providing access to all BBC channels in High Definition. 

The primary goal of this project is **reliability** and **metadata accuracy**. The channel IDs in these playlists are specifically tagged to match perfectly with the **Freeview-EPG** project. This ensures you get accurate show times, descriptions, and channel logos directly from UK Freeview data.

## ✨ Features

* **Complete Collection:** Includes all major BBC TV channels.
* **HD Quality:** All streams are provided in High Definition.
* **EPG Ready:** Pre-configured `tvg-id` tags for instant syncing with `Freeview-EPG`.
* **Themed Logos:** Specialized playlists for Light and Dark player interfaces.

## 🚀 How to Use

### 1. Choose Your Playlist
We offer two versions of the playlist depending on the theme of your IPTV player. This ensures channel logos are clearly visible against your background.

| Theme | Description | Link |
| :--- | :--- | :--- |
| **Dark Mode** | *Best for players with dark backgrounds (White/Light Logos)* | `https://raw.githubusercontent.com/CodingAsteroid/BBC-IPTV/refs/heads/main/All%20HD%20(Dark).m3u` |
| **Light Mode** | *Best for players with light backgrounds (Dark/Color Logos)* | `https://raw.githubusercontent.com/CodingAsteroid/BBC-IPTV/refs/heads/main/All%20HD%20(Light).m3u` |

### 2. Configure the EPG (Electronic Program Guide)
For the program guide to work, you must add the following EPG source URL to your IPTV player settings.

**Source:** `Freeview-EPG`
**URL:** `https://raw.githubusercontent.com/dp247/Freeview-EPG/master/epg.xml`

### 3. Setup Instructions
1.  Open your IPTV Player (e.g., TiviMate, Televizo, Smarters).
2.  **Add Playlist:** Select "Add M3U URL" and paste one of the playlist links from step 1.
3.  **Add EPG:** Navigate to your EPG settings and add the EPG Source URL from step 2.
4.  **Sync:** Ensure the playlist is assigned to use this specific EPG source. The channels should automatically populate with program data.

## 📺 Channel List
* BBC One HD (**All Regions**)
* BBC Two HD
* BBC Three HD
* BBC Four HD
* BBC News HD
* CBBC HD
* CBeebies HD
* BBC Scotland HD
* BBC Parliament

## 👏 Credits
* **EPG Data:** A huge thanks to the [Freeview-EPG](https://github.com/dp247/Freeview-EPG) project for providing the high-quality Electronic Program Guide data used in this playlist.

## ⚠️ Disclaimer
* This repository contains a playlist configuration file only.
* No video files are hosted on this repository.
* This project is not affiliated with the BBC.