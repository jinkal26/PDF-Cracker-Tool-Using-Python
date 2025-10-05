# 🔓 PDF Cracker Tool Using Python

A Python-based tool to crack password-protected PDF files using dictionary-based and brute-force attacks.
This project demonstrates practical applications of file handling, multi-threading, automation, and password security concepts in Python.

# 🎯 Objective

The objective of this project is to develop a tool that can unlock PDF files protected by passwords.
It uses dictionary attacks (wordlists) and brute-force techniques to attempt decryption, providing valuable insight into how password cracking works in cybersecurity.

# 🧩 Project Overview

PDF files are often secured with passwords to prevent unauthorized access.
This tool helps users (for educational and ethical security testing) to understand how password protection mechanisms work — and how they can be improved.

It supports:

Dictionary-based attacks (using wordlists)

Brute-force attacks (generating possible passwords)

Multi-threading for faster password attempts

# ⚙️ How It Works

Input Handling:
Accepts command-line arguments for:

PDF file path

Wordlist file (optional)

Brute-force parameters (length, charset, etc.)

Dictionary Attack:
If a wordlist is provided, the script tests each password from the list sequentially or in parallel.

Brute-Force Attack:
If no wordlist is given, it generates all possible password combinations within given parameters.

Multi-threading:
Uses Python’s ThreadPoolExecutor to test multiple passwords simultaneously for improved performance.

Error Handling:
Handles missing files, unreadable PDFs, and invalid arguments gracefully.

# 🧠 Key Concepts Covered

File handling in Python

Working with PDFs using pikepdf

Dictionary-based and brute-force password attacks

Multi-threading with concurrent.futures

Exception handling for robust and safe execution

# 🧾 Step-by-Step Implementation

1.Install Required Libraries

pip install pikepdf tqdm

2.Run the Script

python pdf_cracker.py file.pdf wordlist.txt

3.Results

Displays the correct password if found

# 📊 Expected Outcomes

By completing this project, you will:

Understand how password cracking works (for ethical use).

Learn multi-threading for performance optimization.

Gain hands-on experience with file handling and PDF manipulation.

Develop a practical tool for cybersecurity and automation learning.

# ⚠️ Disclaimer

This tool is intended for educational and ethical purposes only.
Use it only on files you own or have permission to test.
Unauthorized use on protected content may violate laws or regulations.

# OUTPUT:



Shows progress using tqdm progress bars

Gracefully stops when the correct password is discovered
