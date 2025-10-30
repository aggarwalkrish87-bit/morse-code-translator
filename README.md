# Morse Code Translator — Binary Tree

[![Build](https://img.shields.io/badge/build-pending-lightgrey)]()  <!-- replace with CI badge url when available -->
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A clean, educational implementation of a **Morse Code Translator** built using a **binary tree** representation of dot/dash paths.  
This project demonstrates tree construction and traversal for decoding Morse sequences, plus a simple encoder for converting text → Morse.

---

## Key features
- Encode text to Morse (space between letters, `/` between words)
- Decode Morse to text using a binary tree (dot = left, dash = right)
- Written to be compatible with C++98-style compilers
- Simple console menu for interactive use

---

## Demo

**Encode:**  
`HELLO WORLD` → `.... . .-.. .-.. --- / .-- --- .-. .-.. -..`

**Decode:**  
`.... . .-.. .-.. --- / .-- --- .-. .-.. -..` → `HELLO WORLD`

---

## Files
- `morse_tree_translator.cpp` — main source file (C++98-compatible)
- `README.md` — this file
- `LICENSE` — license file (suggest MIT)
- `.gitignore` — ignores build artifacts
- `.github/workflows/ci.yml` *(optional)* — CI build for Linux/g++ (if you enable Actions)

---

## Build & Run (Linux / macOS / Windows with MinGW)

```bash
# compile (C++98)
g++ morse_tree_translator.cpp -o morse -std=c++98

# run
./morse
