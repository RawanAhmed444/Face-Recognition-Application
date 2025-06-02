# Face Recognition Application

This application is a user-friendly face recognition system using the Eigenfaces method, built with Python and PyQt. It provides an interactive graphical interface for loading, preprocessing, and recognizing faces from images. All core algorithms—including PCA for eigenface computation, face detection, feature extraction, and classification—are implemented from scratch, without relying on external libraries like OpenCV for the main recognition logic.

---

## Features

- **Face Detection & Extraction**
  - Detect and extract faces from images using custom skin color detection (YCrCb), morphological operations, and connected component analysis.
  - Preprocess faces with histogram equalization, normalization, and resizing.

- **Eigenfaces (PCA) Feature Extraction**
  - Compute mean face and eigenfaces from training images.
  - Visualize mean face and top eigenfaces.

- **Face Recognition**
  - Project faces into eigenface space and compute PCA coefficients.
  - Classify test images using Euclidean distance in eigenface space.
  - Support for threshold-based unknown/non-face detection.

- **Interactive GUI**
  - User-friendly PyQt interface for loading datasets, training, testing, and visualizing results.
  - Gallery view for mean face, eigenfaces, and recognition results.

_All core face detection, PCA, and recognition algorithms are implemented from scratch, without using OpenCV for the main processing steps in Python._

---

## Project Structure

```
Task5-Face-Recognition/
  ├── data/
  ├── notebooks/
  ├── resources/
  ├── results/
  ├── src/
  ├── main.py
  └── requirements.txt
```

---

## Screenshots

*Eigenfaces*

![image](https://github.com/user-attachments/assets/a5c20bdb-c4ab-4268-bb34-8dcc400e7d25)

*Reconstructed Faces*

![image](https://github.com/user-attachments/assets/165bb459-5a5b-4604-8c45-79d3e1cd5b3e)

*ROC Curve*

![image](https://github.com/user-attachments/assets/ca3acd41-df96-4173-bd7c-789912c49101)

*Face Recognitioner*

![image](https://github.com/user-attachments/assets/67e715a8-c5ae-44f0-823d-23285a8c02ce)
![image](https://github.com/user-attachments/assets/23b97a45-6dba-4a2f-83e7-541c41892c36)

<!-- Add more screenshots for eigenfaces gallery and recognition results if available -->

---

## Getting Started

### Prerequisites

- Python 3.8+
- PyQt5
- NumPy
- Pillow
- Matplotlib
- SciPy

### Installation

```sh
cd Task5-Face-Recognition
pip install -r requirements.txt
python main.py
```

---

## Contributors

* **Rawan Shoaib**: [GitHub Profile](https://github.com/RawanAhmed444)
* **Ahmed Aldeeb**: [GitHub Profile](https://github.com/AhmedXAlDeeb)
* **Ahmed Mahmoud**: [GitHub Profile](https://github.com/ahmed-226)
* **Eman Emad**: [GitHub Profile](https://github.com/Alyaaa16)

---

## References

- [Eigenfaces for Recognition (Turk & Pentland, 1991)](https://www.face-rec.org/algorithms/PCA/jcn.pdf)
- [PyQt Documentation](https://www.riverbankcomputing.com/static/Docs/PyQt5/)
- [Yale Face Database](http://vision.ucsd.edu/content/yale-face-database)

*You can also have a look at our [report](https://drive.google.com/file/d/1pJwwHaWgvvk8AdPfNX74vb7-3rU-OHxX/view?usp=sharing)*

---
