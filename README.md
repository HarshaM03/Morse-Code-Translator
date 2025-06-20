
# 🔠 Morse Code Translator in Python

A simple Python-based Morse Code Translator that can **encode English text to Morse code** and **decode Morse code back to English**. Ideal for beginners learning about dictionaries, string manipulation, and basic encryption concepts.

---

## 📌 Features

- 🔡 Convert any English **word or sentence** into Morse code
- 🔁 Decode Morse code back to readable English
- ✅ Handles letters (A-Z) and digits (0-9)
- 🛠 Simple and interactive command-line interface

---

## 📷 Demo

```bash
Enter a word to convert to Morse Code: hello
Morse Code: .... . .-.. .-.. ---
Back to English: HELLO
```

---

## 🧠 How It Works

- The script uses a dictionary (`MORSE_CODE_DICT`) to map English characters to their Morse equivalents.
- The `encrypt()` function loops through each character in the input and builds a Morse code string.
- The `decrypt()` function parses Morse code sequences and retrieves the corresponding characters.

---

## 📁 Files

- `morse_translator.py`: Main Python script containing the logic for encoding and decoding.
- `README.md`: Project description and usage guide.

---

## 🚀 Getting Started

### 🔧 Requirements

- Python 3.x

### ▶️ Running the Script

```bash
python morse_translator.py
```

You will be prompted to enter a word. The script will display:
- Morse code translation
- Decoded version back to English

---

## 📚 Morse Code Reference

- A → `.-`
- B → `-...`
- C → `-.-.`
- 1 → `.----`
- 0 → `-----`
- ... and more

---

## 🧑‍💻 Author

**Ramya Manikandan**

---

## 📜 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 💡 Future Enhancements

- 🔊 Add beeping sounds for each Morse symbol
- 🌐 Web-based GUI using Flask or Tkinter
- 📱 Android app version
