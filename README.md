# automatic-file-sorter

## Overview  
This Python script **automatically organizes files** in a specified folder by sorting them into subfolders based on their file type. It identifies file extensions and moves files into their corresponding directories, making file management more effortless.

---

## 🚀 Features  
✅ Scans a folder for files  
✅ Automatically creates subfolders if they don’t exist  
✅ Moves files into their respective subfolders  
✅ Supports common file types:  
- **CSV Files** (`.csv`)  
- **Text Files** (`.txt`)  
- **Image Files** (`.png`)  
- **Python Files** (`.py`)  
- **TSV Files** (`.tsv`)  
- **JSON Files** (`.json`)  

## 📂 Example  

### Before Running the Script  
/Automatic Sorter
  - document.csv
  - image.png
  - script.py
  - notes.txt
  - data.tsv

### After Running the Script  
/Automatic Sorter
  /CSV Files
    - document.csv
  /Image Files
    - image.png
  /Python Files
    - script.py
  /Text Files
    - notes.txt
  /TSV Files
    - data.tsv

---

## 🔧 Potential Improvements  
🔹 Handle duplicate file names by renaming instead of skipping  
🔹 Add support for more file types dynamically  
🔹 Implement logging to track moved files  
