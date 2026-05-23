
# 📦 File Compression System (Huffman + LZW)

## 🚀 Overview

This project is a **File Compression and Decompression System** implemented in Java using advanced Data Structures and Algorithms.

It supports **Huffman Coding** and **LZW Compression**, two widely used lossless compression techniques. The application provides a simple GUI to compress and decompress files efficiently.

---

## 🎯 Features

* ✅ File Compression using Huffman Coding
* ✅ File Compression using LZW Algorithm
* ✅ File Decompression Support
* ✅ GUI-based interface (Java Swing)
* ✅ Supports multiple file formats (.txt, .docx, etc.)
* ✅ Efficient binary encoding and decoding

---

## 🧠 Algorithms Used

### 🔹 Huffman Coding

* Greedy Algorithm
* Uses Binary Tree
* Assigns shorter codes to frequent characters

### 🔹 LZW Compression

* Dictionary-based compression
* Dynamic encoding
* Efficient for repeated patterns

---

## 🛠️ Tech Stack

* Java
* Maven
* Data Structures & Algorithms
* File Handling
* Java Swing (GUI)

---

## ⚙️ How to Run

### Step 1: Clone the repository

```bash
git clone https://github.com/Ajinkyarodge66/file-compression-dsa.git
cd file-compression-dsa
```

### Step 2: Build project

```bash
mvn clean install
```

### Step 3: Run application

```bash
mvn exec:java
```

---

## 📌 How to Use

### 🔹 Compression

1. Select a file (e.g., `.txt`, `.docx`)
2. Choose algorithm (Huffman / LZW)
3. Compressed file will be generated

### 🔹 Decompression (IMPORTANT)

* Select the **compressed file only**

  * `.huffz` (Huffman)
  * `.LmZWp` (LZW)
* ❌ Do NOT select original file

---

## 📊 Example

| Operation  | Input File      | Output File     |
| ---------- | --------------- | --------------- |
| Compress   | file.docx       | file.docx.huffz |
| Decompress | file.docx.huffz | file.docx       |

---

## ⚠️ Known Issues

* Compression ratio calculation may show incorrect values (can be improved)
* Limited support for very large files

---

## 🚀 Future Improvements

* Add drag & drop UI
* Improve compression ratio accuracy
* Support images and binary files
* Add real-time compression statistics
* Web-based version

---

## 👨‍💻 Author

**Ajinkya Asaram Rodge**
Computer Science Student

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!

---
