A lightweight web application for compressing and decompressing text files using **Huffman Coding**, implemented with a C++ backend and a Python Flask web interface.

## 🚀 Features

- **Lossless file compression** using the Huffman coding algorithm.
- **Web-based interface** to upload files and see compressed output.
- **C++ backend** for high-performance compression logic.
- **Python Flask server** for smooth web integration.
- Minimal UI built with **HTML, CSS, and JavaScript**.

## 🛠️ Tech Stack

- **C++** – Huffman encoding/decoding logic (`huffmancomp.cpp`)
- **Python Flask** – Web server and routing (`server.py`)
- **HTML/CSS/JS** – Frontend for file upload and display
- **File I/O** – Upload and process `.txt` files

## 📂 Project Structure

```
Huffman Compression Web-app/
├── huffmancomp.cpp               # C++ source file for compression
├── input.txt                     # Sample input file
├── huffman-web/
│   ├── server.py                 # Flask server
│   ├── templates/index.html      # Frontend UI
│   ├── static/
│   │   ├── script.js
│   │   └── style.css
│   ├── uploads/                  # Stores input/output text files
│   │   ├── input.txt
│   │   └── input_output.txt
│   └── huffmancomp.exe           # Compiled C++ executable
```

## 🧪 How to Run

### 1. Compile C++ Code (If needed)

```bash
g++ huffmancomp.cpp -o huffmancomp.exe
```

### 2. Run Flask Server

```bash
cd huffman-web
python server.py
```

### 3. Access the Web App

Open your browser and go to:

```
http://localhost:5000
```

## 📌 Notes

- Make sure Python and Flask are installed.
- The app processes `.txt` files placed in the `uploads/` directory.
- Compression and decompression is handled by the compiled C++ binary.
