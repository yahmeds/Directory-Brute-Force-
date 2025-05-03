# Directory-Brute-Force

A simple directory brute-force tool written in Java.  
It performs wordlist-based enumeration by appending paths to a base URL and checking for valid responses.

---

## 🧠 Features

- Appends each line of a given wordlist to a base URL.
- Sends HTTP GET requests to detect existing directories or endpoints.
- Displays discovered paths and their HTTP status codes.
- Skips 404 errors by default (assumes non-existent resources return 404).

---

## 🛠️ Requirements

- Java 8 or higher
- Internet connection
- A target URL (must be valid and reachable)
- A text file (.txt) containing the wordlist (one directory per line)

---

## 🚀 Usage

Compile the Java file:
```bash
javac Brut.java
```

Run the tool 
```bash
java Brut <base_url> <wordlist.txt>
```
