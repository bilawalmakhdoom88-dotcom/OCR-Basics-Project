# 🧾 OCR Basics Project (Tesseract &  Easy OCR)

## 📌 Overview

This project demonstrates the basics of **Optical Character Recognition (OCR)** using two popular libraries:

* **Tesseract OCR**
* **Easy OCR**

It also explores how **image preprocessing techniques** can improve text extraction accuracy.

The notebook is divided into multiple parts, each focusing on a specific concept of OCR.

---

## ⚙️ Technologies Used

* Python
* OpenCV (`cv2`)
* Tesseract OCR 
* Easy OCR
* PIL (Python Imaging Library)
* NumPy & Pandas
* Matplotlib

---

## 📂 Project Structure

### 🔹 Part 1: Tesseract OCR

* Perform basic text extraction from images
* Extract **confidence scores** for detected text
* Understand how Tesseract processes images

#### Tasks:

* **Task 1.1**: Basic Text Extraction
* **Task 1.2**: Confidence Score Analysis

---

### 🔹 Part 2: Easy OCR

* Initialize Easy OCR reader
* Extract text with bounding boxes and confidence levels
* Compare with Tesseract results

#### Tasks:

* **Task 2.1**: Initialize Easy OCR
* **Task 2.2**: Text Extraction

---

### 🔹 Part 3: Image Preprocessing

Improves OCR accuracy using:

* Grayscale conversion
* Noise reduction (Gaussian Blur)
* Thresholding techniques

#### Tasks:

* **Task 3.1**: Grayscale Conversion
* **Task 3.2**: Noise Reduction & Thresholding

---

### 🔹 Part 4: Comparison

* Compare results from:

  * Raw images
  * Preprocessed images
* Evaluate which OCR method performs better

---

## 📸 Dataset

Images are loaded from a dataset directory (Kaggle path used in notebook):

```
/kaggle/input/datasets/bilawal/ai-lab-5/images/
```

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install pytesseract easyocr opencv-python pillow matplotlib numpy pandas
```

2. Ensure Tesseract is installed:

```bash
tesseract --version
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 💡 Key Learnings

* Difference between **Tesseract OCR** and **EasyOCR**
* Importance of **image preprocessing**
* How confidence scores help evaluate OCR results
* Practical implementation of OCR pipelines

---

## 📊 Output

* Extracted text from images
* Confidence scores for predictions
* Improved results after preprocessing
* Comparison of OCR engines

---

## 🔚 Conclusion

This project highlights how combining OCR tools with preprocessing techniques can significantly improve text recognition accuracy. It also provides a practical understanding of working with real-world image data.

---

## 👨‍💻 Author

Makhdoom Bilawal

---
