# 📝 Java Swing Text Editor

A **Notepad-like Text Editor** built in **Java Swing** with features like file operations, text editing, search/replace, font customization, and printing support. This project is a lightweight, GUI-based application for creating and editing text files.

---

## 📌 Features

✅ **File Operations**  
- New, Open, Save, Save As  
- Page Setup & Print  
- Automatic `.txt` extension handling  

✅ **Edit Options**  
- Cut, Copy, Paste, Delete  
- Find & Replace text  
- Go to specific line number  
- Select All  
- Insert timestamp  

✅ **Formatting Options**  
- Word Wrap (toggle on/off)  
- Font chooser (select font, size, bold, italic)  

✅ **Help Menu**  
- About dialog  

✅ **User-Friendly Interface**  
- Scrollable text area  
- Title bar updates with file name  
- Error handling for invalid operations  

---

## 🛠️ Technologies Used

- **Java Swing** – GUI components (JFrame, JMenu, JTextArea, JOptionPane)
- **Java I/O** – File handling (`BufferedReader`, `BufferedWriter`, `FileChooser`)
- **OOP Concepts** – Modular design (separate class `JFontChooser` for font dialog)
- **Event Handling** – Implements `ActionListener` for menu actions

---

## 📂 Project Structure

```

TextEditor/
│
├── TextEditor.java   # Main class with GUI, file operations, and menu handling
├── JFontChooser.java # Custom font chooser panel for font selection
└── Readme.md

```

---

## ▶️ How to Run

1. **Clone or Download** the project  
   ```bash
   git clone https://github.com/Sushovanbarik/Text-Editor-using-java
   cd java-text-editor
   ```

2. **Compile the Source Files**

   ```bash
   javac TextEditor.java JFontChooser.java
   ```

3. **Run the Application**

   ```bash
   java TextEditor
   ```

---


## 🧾 Example Usage

### 1. Opening a File

* Go to **File → Open**
* Select a `.txt` file → Contents will be loaded into the text area.

### 2. Finding and Replacing Text

* Go to **Edit → Replace**
* Enter the text to find and the replacement text → Click OK.

### 3. Changing Font

* Go to **Format → Font**
* Choose desired font family, size, and style → Click OK.

---

## 🏗️ Future Improvements

* Add **Syntax Highlighting** for code editing.
* Add **Undo/Redo** functionality.
* Add **Multiple Tab Support** for working with multiple files.
* Add **Dark Mode**.

---

## 👨‍💻 Author

* **Sushovan Barik**
* 📧 [sushovanbarik66@gmail.com](mailto:sushovanbarik66@gmail.com)
* 🌐 [LinkedIn](http://www.linkedin.com/in/sushovan-barik-8b41b6268)

---
