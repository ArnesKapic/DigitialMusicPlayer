# 🎵 Digital Music Player - Final Project

**Author:** Arnes Kapic    
**Project:** Final Python Music Playlist Application  

## 📌 Overview

This project is a command-line-based Digital Music Player, developed as a start-up for a project. It allows users to create, manage, and interact with a custom playlist of songs. The application uses core object-oriented programming principles and data structures such as **linked lists** and **stacks** to simulate music playlist behavior with features like undo, search, and automatic sorting.

## ⚙️ Features

- 🎶 Add, play, delete, and search songs in your playlist  
- 🔁 Undo the last song addition or deletion using a stack-based history  
- 📋 Display the full playlist with artist and genre info  
- 🔍 Check if a song exists and view its details  
- 📊 Count the total number of songs  
- ❌ Clear all songs on exit

## 🧠 Technical Concepts Used

- **Linked Lists** – Songs are stored in nodes linked together to represent the playlist  
- **Stacks** – Keeps a history of previous playlist states to allow undo functionality  
- **Deep Copying** – Ensures playlist states are preserved accurately  
- **Modular Design** – Functions are broken down for clarity and reusability  
- **Rich Library** – Used for enhanced terminal menu formatting

## 💡 How It Works

When you run the program, you'll see a rich-formatted menu where you can:
- Add songs (sorted by name)
- Play specific songs
- Undo recent changes
- Delete songs
- View or search your playlist
- Exit the program (which clears your playlist)

Each option triggers functionality built around custom `Node` and `Stack` classes with user-friendly prompts and validations.

## 📁 Running the Program

Ensure you have Python installed and run the following command:

```bash
python digital_music_player.py

