[README.md](https://github.com/user-attachments/files/27299281/README.md)
# 🚗 ANPR - Automatic Number Plate Recognition

A computer vision-based system that detects and extracts vehicle license plates from images using OpenCV and Python.

---

## 📌 About

This project implements an **Automatic Number Plate Recognition (ANPR)** pipeline that processes vehicle images to automatically detect, segment, and extract license plate text using image processing and OCR techniques.

---

## ✨ Features

- 🔍 Detects license plates from vehicle images
- 🔤 Extracts and recognizes plate characters using OCR
- ⚡ Fast and lightweight — built with OpenCV and Python
- 🖼️ Supports common image formats (JPG, PNG, etc.)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| OpenCV | Image processing & plate detection |
| Tesseract OCR / EasyOCR | Character recognition |
| NumPy | Array & image manipulation |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed, then install the required libraries:

```bash
pip install opencv-python numpy pytesseract easyocr
```

Also install **Tesseract OCR** on your system:
- **Windows:** [Download here](https://github.com/UB-Mannheim/tesseract/wiki)
- **Linux:** `sudo apt install tesseract-ocr`
- **Mac:** `brew install tesseract`

### Installation

```bash
# Clone the repository
git clone https://github.com/Saurabh0cd/number-plate-extraction/blob/main/live_number_plate_extraction.ipynb

# Navigate into the project
cd live_number_plate_extraction

# Install dependencies
pip install -r requirements.txt
```

---

## 🖼️ Usage

```bash
python main.py --image path/to/your/image.jpg
```

### Example

```bash
python main.py --image test_images/car1.jpg
```

**Output:**
```
Detected Plate: KA 01 AB 1234
```

---

## 📁 Project Structure

```
anpr-number-plate-extraction/
│
├── main.py               # Main script
├── detector.py           # Plate detection logic
├── ocr.py                # Character recognition
├── utils.py              # Helper functions
├── test_images/          # Sample input images
├── output/               # Processed output images
├── requirements.txt      # Dependencies
└── README.md
```

---

## 📸 Sample Output

> Input image → Detected plate region → Extracted text

*(Add a screenshot or demo GIF here)*

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
