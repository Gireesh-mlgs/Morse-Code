# 📡 Morse Code Converter & Sound Player

A simple Python application that converts text into **Morse code** and plays it as audible beeps. The program supports letters, numbers, punctuation, and spaces, making it a great beginner project for learning dictionaries, functions, and timing in Python.

---

## ✨ Features

- 🔤 Convert text to Morse code
- 🔊 Play Morse code as sound
- 🖥️ Cross-platform support
  - Windows: Uses `winsound.Beep()`
  - Linux/macOS: Uses the system bell (`\a`)
- 🔢 Supports letters (A–Z)
- 🔟 Supports numbers (0–9)
- ❗ Supports common punctuation marks
- 🚀 Lightweight with no external dependencies

---

## 📋 Requirements

- Python 3.8 or later

No third-party libraries are required.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Gireesh-mlgs/Morse-Code
cd Morse-Code
```

Run the program:

```bash
python app.py
```

---

## 💻 Usage

After running the script, enter any text:

```text
Enter text to convert to Morse code:
Hello World
```

Output:

```text
Morse Code:
.... . .-.. .-.. --- / .-- --- .-. .-.. -..
```

The program will then play the Morse code using audible beeps.

---

## 📂 Project Structure

```
morse-code-converter/
│
├── morse.py
├── README.md

```

---

## ⚙️ How It Works

1. Accepts text input from the user.
2. Converts each character into its Morse code equivalent using a dictionary.
3. Prints the generated Morse code.
4. Plays each Morse symbol:
   - **Dot (.)** → Short beep (100 ms)
   - **Dash (-)** → Long beep (300 ms)
   - **Space** → Pause between letters
   - **/** → Pause between words

---

## 🛠️ Technologies Used

- Python
- `time`
- `platform`
- `winsound` (Windows)
- `os`

---

## 📚 Morse Code Timing

| Symbol | Duration |
|---------|----------|
| Dot (`.`) | 100 ms |
| Dash (`-`) | 300 ms |
| Letter Gap | 300 ms |
| Word Gap | 700 ms |

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a Pull Request.


---

⭐ If you found this project useful, consider giving it a star!
