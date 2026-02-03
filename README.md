# Computer Vision Lab – 3  
**OpenCV & scikit-image Feature Detection Experiments**

This repository contains the complete implementation and documentation for **Computer Vision Lab-3**, focusing on feature detection and multi-scale image analysis using **OpenCV** and **scikit-image**.  
The experiments are implemented and tested on **Google Colab**.

---

## 📌 Objectives
The objectives of this lab are to:
- Perform **Blob Detection** using Laplacian of Gaussian (LoG)
- Implement **Harris Corner Detection**
- Construct **Gaussian and Laplacian Image Pyramids**
- Apply **Gabor Filter Banks** for texture analysis
- Understand multi-scale and orientation-based feature extraction techniques

---

## 🧪 Experiments Performed

### 1. Blob Detection
- Detects regions that differ in intensity from their surroundings
- Implemented using **Laplacian of Gaussian (LoG)**
- Useful for detecting circular or blob-like structures

### 2. Harris Corner Detection
- Identifies corner points based on intensity variation
- Uses eigenvalues of the second moment matrix
- Commonly used in feature matching and object recognition

### 3. Image Pyramids
- **Gaussian Pyramid**: Downsamples image to lower resolutions  
- **Laplacian Pyramid**: Captures edge information between pyramid levels  
- Used in multi-scale image processing

### 4. Gabor Filter Banks
- Extracts texture features at different orientations and frequencies
- Useful for texture classification and pattern recognition

---

## 🗂️ Folder Structure

```
CV_Lab_3/
│── README.md
│── CV_Lab_3_Report.docx
│── CV_Lab_3_Report.pdf
│── code/
│ └── cv_lab_3.ipynb
│── input/
│ └── sudoku.png
│── output/
│ ├── blob_detection.png
│ ├── harris_corners.png
│ ├── pyramids.png
│ └── gabor_filters.png
```


---

## ⚙️ Technologies Used
- Python 3.x
- OpenCV
- scikit-image
- NumPy
- Matplotlib
- Google Colab

---

## ▶️ How to Run (Google Colab)

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/CV_Lab_3.git

2. Open the notebook:

Upload cv_lab_3.ipynb to Google Colab

3. Install dependencies:

!pip install opencv-python scikit-image matplotlib


4. Run all cells sequentially to view results.


**Report**

The detailed lab report is available in the following formats:

CV_Lab_3_Report.docx

CV_Lab_3_Report.pdf

The report includes:

Objective

Theory

Procedure

Observations

Results

🎯 Results

Blob regions were successfully detected using LoG

Harris corner detector accurately identified corner points

Image pyramids demonstrated effective multi-scale representation

Gabor filters extracted orientation-based texture features

🧑‍🎓 Author

Your Name
M.Tech – Computer Science / AI / Computer Vision
Your University Name

📚 References

OpenCV Documentation – Blob Detection

OpenCV Documentation – Harris Corner Detection

OpenCV Documentation – Image Pyramids

scikit-image Documentation – Gabor Filters


