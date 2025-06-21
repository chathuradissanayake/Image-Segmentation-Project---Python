
# 🧠 Image Segmentation Tasks in Python

This project contains two core image segmentation tasks implemented using Python and Jupyter Notebooks.

## 📁 Project Structure

```
image_segmentation_project/
│
├── notebooks/                            # Task notebooks
│   ├── task1_otsu_thresholding.ipynb
│   └── task2_region_growing.ipynb
│
├── outputs/                              # Generated output images
│   ├── task1/
│   └── task2/
│
├── requirements.txt                      # Python dependencies
└── README.md                             # Project documentation
```

---

## 🚀 Tasks Overview

### ✅ Task 1: Otsu's Thresholding with Gaussian Noise
- Generate a synthetic grayscale image with 3 intensity levels (background + 2 objects)
- Add Gaussian noise to the image
- Apply Otsu’s thresholding to separate foreground and background
- Save and visualize the thresholded result

### ✅ Task 2: Region Growing Segmentation
- Start from a user-defined seed point inside an object
- Grow the region by including neighboring pixels within a defined intensity range
- Return a binary mask representing the segmented object
- Adjustable threshold and seed position

---

## 🧪 How to Run

1. Clone or download this project
2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Launch Jupyter and open notebooks:
    ```bash
    jupyter notebook notebooks/
    ```
4. Run each cell step-by-step and inspect the results

---

## 💾 Output

Segmented and processed images are automatically saved to the `outputs/` directory under their respective task folders.

---

## 👨‍💻 Dependencies

- Python 3.8+
- numpy
- pillow
- opencv-python
- matplotlib
- jupyter

---

## 📸 Notes
You can use your own grayscale images by replacing or loading them in the notebook if desired.
