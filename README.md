# 🧠 FlashMind — Flashcard Quiz App

A clean, simple flashcard app built to make studying actually enjoyable. No accounts, no clutter — just you and your cards.

---

## What is this?

FlashMind is a browser-based flashcard app where you can create your own study cards, flip through them, and quiz yourself on anything — whether that's exam prep, learning a new language, memorising code concepts, or just random facts you want to remember.

It's a single HTML file, so there's nothing to install. Just open it in your browser and start studying.

---

## Features

- **Flip cards** to reveal the answer — click the card or hit `Space`
- **Navigate** between cards with Prev / Next buttons or your arrow keys ← →
- **Progress bar** so you always know how far through the deck you are
- **Add your own cards** with any question and answer you like
- **Edit cards** if you made a typo or want to improve an answer
- **Delete cards** you no longer need
- Comes with **5 sample cards** out of the box so you can see how it works right away

---

## How to use it

1. Open `flashcard_app.html` in any browser
2. Click a card (or press `Space`) to flip it and see the answer
3. Use **Prev** / **Next** (or arrow keys) to move between cards
4. Click **⚙ Manage Cards** at the bottom to add, edit, or delete cards

That's it. No login, no setup, no fuss.

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Flip the current card |
| `→` Arrow | Next card |
| `←` Arrow | Previous card |

---

## Running it locally (VS Code)

If you want to edit and preview the app live:

1. Install the **Live Server** extension in VS Code
2. Open the project folder in VS Code
3. Click **Go Live** in the bottom-right corner
4. The app opens in your browser and refreshes automatically when you save changes

---

## Project Structure

```
flashcard-app/
│
├── flashcard_app.html   # The entire app — HTML, CSS, and JS in one file
└── README.md            # You're reading this
```

Everything lives in a single file, which keeps things simple and easy to share.

---

## Built With

- Plain HTML, CSS, and JavaScript — no frameworks, no dependencies
- Google Fonts (Playfair Display + DM Sans)
- A bit of CSS animation for the card flip effect

---

## Want to customise it?

Open `flashcard_app.html` in any text editor. The code is split into three sections:

- **Styles** (inside `<style>`) — change colours, fonts, spacing
- **HTML** (the body) — change the layout and structure
- **JavaScript** (inside `<script>`) — change the logic or add new features

The default cards are defined right at the top of the `<script>` section in a simple array — easy to edit.

---

## Future Ideas

A few things that could make this even better down the road:

- Shuffle mode to randomise card order
- Score tracking (mark cards as known / still learning)
- Local storage so cards are saved between sessions
- Import / export cards as a file
- Multiple decks

---

## Made by

**Sourish** — built as part of the CodeAlpha internship project.

Feel free to fork it, break it, improve it. 🚀
