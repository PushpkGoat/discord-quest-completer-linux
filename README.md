# 🐉 Discord Quest Completer (Linux)
Doesnt really complete quests as of new discord update but can still spoof your activity status to whatever game you want.
(Actually it isnt completely made by me and is just fork of [https://github.com/markterence/discord-quest-completer])

A lightweight desktop application built with Tauri and Rust that allows you to complete Discord Quests without downloading, installing, or playing the actual games. 

This is a specialized Linux build designed for users who want to earn rewards without the storage burden or anti-cheat requirements of large titles.

## ✨ Features
- **Zero Install:** Complete 15-minute "Play" quests without downloading 50GB+ game files.
- **Linux Native:** Specifically patched and compiled for Linux (tested on Kali).
- **Safe & Fast:** Uses tiny dummy processes to mimic game activity for Discord detection.
- **Low Resource:** Runs with minimal CPU and RAM usage.

## 📥 How to Use (Pre-compiled Binary)
You don't need to build this from source! Just follow these steps:

1. **Download** the `discord-quest-completer` file from the [Releases](https://github.com/PushpkGoat/discord-quest-completer-linux/releases) page.
2. **Open Terminal** in the download folder.
3. **Give Permission** to run:
   ```bash
   chmod +x discord-quest-completer
4. **Launch the App:** ```./discord-quest-completer```

## 🛠 Prerequisites for Linux 
  If the app doesn't open, ensure you have the WebKit library installed:
    
    
    sudo apt update && sudo apt install libwebkit2gtk-4.1-dev -y
    


