# hangman-v2

# Pygame Hangman

A graphical Hangman game built with **pygame**, with optional **NLTK** word corpus support.

NLTK words corpus (recommended)

If you installed NLTK, download the words corpus once:

python -c "import nltk; nltk.download('words')"


If NLTK (or the corpus) is unavailable, the game automatically falls back to a built-in word list.

Controls

Click letters on-screen, or type letters on your keyboard

Use the HINT button (max 3 hints)

Choose difficulty from the main menu
## Run locally

```bash
pip install -r requirements.txt
python hangman.py

