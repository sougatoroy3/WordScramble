# 🧠 WordScramble - SwiftUI Game

A fun, simple word game built with SwiftUI! Players are given a random root word and must come up with as many valid English words as possible using only the letters from the root word.

---

## 📱 Features

- 📝 Type in your words via a `TextField`
- 🔤 Automatic validation for:
  - Unused (original) words
  - Words made from the root word
  - Valid English words using `UITextChecker`
- ⚠️ Alerts for invalid entries
- 📃 Track entered words with icons showing their length
- 🔄 Loads random root word from a `start.txt` file in the bundle

---

## 🛠 Built With

- Swift 5
- SwiftUI
- UIKit (`UITextChecker` for spell-checking)

---

## 📂 Project Structure

- **`ContentView.swift`** — Main view and logic for the game
- **`start.txt`** — List of root words (placed in the app bundle)

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/WordScramble-SwiftUI.git
2. Open the project in Xcode.
3. Add a start.txt file to your app bundle with a list of words, one per line:
silkworm
developer
keyboard
swift
...
4. Run the app on a simulator or physical device.

## 🧠 How It Works
When the app starts, it loads a list of words from start.txt.
A single word is randomly selected as the root word.
Users must enter as many real English words as possible that:
Use only the letters from the root word
Have not already been used
Are real, valid English words
