# Document Scanner using OpenCV 📄🔍

## 📌 Introduction
This project implements a **Document Scanner** using **OpenCV**. The goal is to detect documents in an image, extract their corners, and apply a **Perspective Transform** to create a neatly cropped and corrected version of the document.

## 🚀 Features
- **Edge Detection**: Using **Canny Edge Detection** to identify document contours.
- **Contour Detection**: Extracting the largest quadrilateral as the document.
- **Perspective Transformation**: Warping the document to a flat, standard view.
- **Preprocessing Techniques**:
  - Grayscale Conversion
  - Gaussian Blurring
  - Adaptive Thresholding for improved detection
- **Multiple Document Extraction**: Detecting multiple documents in one image.

## 📂 Project Structure
```
📦 Document-Scanner
├── 📜 machine_vision_.ipynb   # Jupyter Notebook with full implementation
├── 📜 Doc.jpg                # Sample document image
├── 📜 README.md              # Project documentation
├── 📜 Pipes.jpg              # Sample  image
```



## 📌 How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook machine_vision_.ipynb
   ```
2. Run all cells sequentially to execute document detection and perspective transformation.

## 📊 Results Analysis
- **Edge & Contour Detection**: Visualizing detected edges and contours.
- **Perspective Correction**: Transforming the detected document into a neatly aligned scan.
- **Enhancement Options**: Exploring adaptive thresholding and contrast adjustments for better readability.

## 📧 Contact
For any inquiries or collaboration opportunities, reach out to:
📩 Email: emad.k50000@gmail.com

## ⭐ Contribute
Feel free to fork this repository, report issues, or submit pull requests to improve the project.

🔹 **Developed by [Emad K] | Open Source & Research-Oriented**

