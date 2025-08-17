# File Organizer 🗂️

This Python script is a **file organizer** that automatically sorts files in a selected directory into subfolders based on their file type (e.g., images, documents, videos). 🧹

---

## Features ✨

* **Automatic Sorting**: Organizes files by their extension into dedicated folders like "Images," "Documents," "Videos," etc.
  
* **Intuitive Interface**: Uses a simple graphical user interface (GUI) to let you easily select the folder you want to clean up. 🖱️
  
* **Handles Various File Types**: Supports a wide range of common file extensions, including PDFs, images, videos, audio, code files, and more. Any unrecognized file types are moved to a folder called "Others." 📁
  
* **Error Handling**: The script checks if the selected directory exists before attempting to organize the files, preventing errors. 🛡️

---

## How to Use 🚀

1.  **Run the Script**: Execute the Python script.
2.  **Select a Directory**: A dialog box will appear. Select the folder containing the files you want to organize.
3.  **Watch it Work**: The script will create new folders and move the files into their appropriate categories. 🪄

---

## File Type Mapping 🗺️

The script uses a dictionary to map file extensions to specific folder names. Here's a quick look at how some file types are categorized:

* `.jpg`, `.png`, `.gif` → `Images` 🖼️
* `.pdf`, `.doc`, `.docx` → `Documents` 📄
* `.mp4`, `.mov`, `.avi` → `Videos` 🎬
* `.py`, `.js` → `Python_Scripts`, `JavaScript_Files` 🐍
* `.zip`, `.rar` → `Archives` 📦

Any other file extensions that are not explicitly listed will be moved to the **Others** folder.
