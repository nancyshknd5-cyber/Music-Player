# Music-Player
This project is a console-based Music Player application written in C, designed using core Data Structures concepts like Doubly Linked List, Stack, and Queue. It simulates real-world music player functionalities with additional interactive and visual features.
Add files via upload
# 🎵 Music Player Pro in C

A console-based Music Player application built using C Programming and Data Structures.  
This project demonstrates real-world implementation of Doubly Linked List, Stack, and Queue.

---

## 🚀 Features

- 🎧 Play current song  
- ⏭️ Next and ⏮️ Previous song navigation  
- ➕ Add new songs to playlist  
- ❌ Delete songs  
- 🔍 Search songs (partial match supported)  
- 📊 Track how many times a song is played  
- 🏆 Show most played song  
- 📜 Display playlist with current playing highlight  
- 🔁 Queue system (FIFO)  
- 🔙 Previous songs using Stack (LIFO)  
- 🔗 Linked List visualization  
- 🔊 Sound effects using Beep()  
- 🎨 Colored console output  

---

## 🧠 Data Structures Used

### 1. Doubly Linked List
- Used to store songs
- Each node contains:
  - Song name
  - Play count
  - Previous and Next pointer

### 2. Stack (LIFO)
- Used to store previously played songs  
- Helps in "Previous" functionality  

### 3. Queue (FIFO)
- Used for song queue system  
- Songs play in order they are added  

---

## 💻 Technologies Used

- C Programming Language  
- Standard Libraries:
  - stdio.h
  - stdlib.h
  - string.h  
- Windows Library:
  - windows.h (for sound using Beep)  
- Console UI with ANSI Colors  

---

## 📂 Project Structure
