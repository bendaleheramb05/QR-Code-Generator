# 📱 QR Code Generator in Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Library-qrcode-success" />
  <img src="https://img.shields.io/badge/Pillow-Image%20Processing-orange" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" />
  <img src="https://img.shields.io/badge/License-MIT-blue" />
</p>

<p align="center">
  <b>A simple and efficient Python application that generates QR codes from text, URLs, phone numbers, emails, or any custom data.</b>
</p>

---

## 📖 Project Overview

The **QR Code Generator** is a beginner-friendly Python project that converts user input into a QR code image.

Users can enter:

* 🌐 Website URLs
* 📝 Plain Text
* 📞 Phone Numbers
* 📧 Email Addresses
* 📍 Any Custom Information

The application instantly generates a QR code and saves it as a **PNG image** inside the **output** folder.

---

## 🚀 Features

* ✅ Generate QR codes instantly
* ✅ Accept any text or URL
* ✅ Automatically create the output folder
* ✅ Save QR codes as PNG images
* ✅ Beginner-friendly code
* ✅ Lightweight and fast
* ✅ Easy to customize

---

## 🛠️ Technologies Used

| Technology | Purpose                |
| ---------- | ---------------------- |
| Python     | Programming Language   |
| qrcode     | QR Code Generation     |
| Pillow     | Image Processing       |
| OS Module  | File & Folder Handling |

---

## 📂 Project Structure

```text
QR-Code-Generator/
│
├── qr_generator.py
├── requirements.txt
├── README.md
│
├── output/
│   └── my_qr.png
│
└── screenshots/
    ├── terminal_output.png
    └── generated_qr.png
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username
/QR-Code-Generator.git
```

### Move into Project

```bash
cd QR-Code-Generator
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

or

```bash
pip install qrcode pillow
```

---

## ▶️ Run the Project

```bash
python qr_generator.py
```

---

## 💻 Example

### Input

```text
Enter text or URL:

https://github.com
```

### Output

```text
QR Code saved successfully!

Location:
output/my_qr.png
```

---

## 📸 Output

After running the program:

```text
output/
└── my_qr.png
```

Open the generated image and scan it with any smartphone camera or QR Scanner.

---

## 📷 Screenshots

### Terminal Output

```
(Add terminal_output.png here)
```

### Generated QR Code

```
(Add generated_qr.png here)
```

After adding screenshots:

```markdown
![Terminal](screenshots/terminal_output.png)

![QR Code](screenshots/generated_qr.png)
```

---

## 📦 requirements.txt

```text
qrcode
Pillow
```

---

## 🔄 Workflow

```text
User Input
      │
      ▼
Read Text / URL
      │
      ▼
Generate QR Code
      │
      ▼
Create PNG Image
      │
      ▼
Save Inside Output Folder
      │
      ▼
Ready to Scan
```

---

## 🎯 Learning Outcomes

This project helped in understanding:

* Python packages
* Third-party libraries
* User input handling
* Image generation
* File handling
* Folder management
* Basic project structure

---

## 🔮 Future Enhancements

* 🎨 Custom QR Colors
* 🖼️ Add Logo in Center
* 🖥️ Tkinter GUI Version
* 🌙 Dark Theme QR
* 📁 Batch QR Generator
* 📄 Export as SVG & PDF
* ☁️ Cloud Storage Support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

## 👨‍💻 Author

**Heramb Bendale**

Python Developer | Data Science Enthusiast

GitHub: https://github.com/bendaleheramb05


---

<p align="center">
Made with ❤️ using Python
</p>
