# 🎮 Hangman Deluxe — Modern Pygame Edition

A **polished, feature-rich Hangman game** built with **Python + Pygame**, designed to be **easy to run**, **easy to package**, and **fun to play**.

No NLTK.  
No corpora headaches.  
No virtual environments required for players.

---

## ✨ Features

✅ Clean, modern **graphical interface (Pygame)**  
✅ **3,000 or 5,000 common English words** (toggle in menu)  
✅ **Thematic word packs**  
  • Common  
  • Tech  
  • Food  
  • Animals  
  • Space  
  • Sports  
  • Geography  
✅ **Difficulty modes**: Easy / Medium / Hard  
✅ **Hint system** (limited, score-aware)  
✅ **Score tracking across games**  
✅ **Offline play** (words cached locally)  
✅ **Single-file executable support** via PyInstaller  
✅ Cross-platform: **Linux / Windows / macOS**

---

## 🧠 Difficulty System (Smart & Balanced)

Each difficulty dynamically filters words by length:

| Difficulty | Word Length | Attempts |
|----------|------------|----------|
| Easy | 4–6 letters | 8 |
| Medium | 6–9 letters | 7 |
| Hard | 9–15 letters | 6 |

Word pools are **auto-balanced** to ensure variety without repetition.

---

## 🗂️ Thematic Word Packs

Switch themes directly from the menu:

- 💻 **Tech** — programming & computing terms  
- 🍕 **Food** — ingredients, meals, flavours  
- 🐾 **Animals** — land, sea, and air  
- 🚀 **Space** — astronomy & sci-fi vocabulary  
- 🏅 **Sports** — teams, activities, fitness  
- 🌍 **Geography** — natural features & climate  

Themes are blended with common words to maintain difficulty balance.

---

## 📦 Installation (Developers)

### Requirements
- Python **3.10+**
- `pygame`

```bash
pip install pygame
python hangman.py
🧊 No NLTK, No Corpora, No Hassle
This project intentionally does NOT use NLTK.

Why?

❌ No runtime downloads

❌ No WordNet issues

❌ No broken PyInstaller builds

✅ Smaller binaries

✅ Faster startup

✅ Easier maintenance

Words are sourced from a curated Top-10,000 frequency list, cached on first download and reused offline.

🧰 Build a Single Executable (PyInstaller)
Create a standalone binary — no Python required for players.

bash
Copy code
pip install pyinstaller
pyinstaller --onefile --windowed hangman.py
Output:

bash
Copy code
dist/hangman
Distribute it like a normal game.

🖥️ UI Highlights
Large 1200×900 window (no cramped UI)

Centered keyboard layout

Clear visual hierarchy

Responsive spacing for all screens

Designed for keyboard and mouse input

📜 License
MIT License — free to use, modify, and distribute.

🙌 Credits
Word frequency data inspired by public English frequency lists

Built with ❤️ using Python & Pygame

⭐ If you like this project, give it a star!
