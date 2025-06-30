
# Image Transformations and Contour Detection with OpenCV

This project demonstrates key computer vision techniques using **Python** and **OpenCV**, including geometric image transformations and contour detection. It explores image flipping, rotation, blurring, and shape boundary extraction, which are foundational tools for preprocessing and analyzing images in computer vision pipelines.

> Project developed as part of coursework at **Capella University**  
> Learn to manipulate and extract structure from visual data.

---

## Features

- Flip, rotate, and blur images using OpenCV
- Detect contours and edges from grayscale images
- Draw and annotate contours and bounding boxes
- Save transformed and annotated output images

---

## Project Structure

```bash
.
├── ImageTransformations_ContourDetection.ipynb  # Main notebook
├── sample_images/
│   ├── simple-features_base_1.jpg
│   ├── simple-features_base_2.png
│   ├── simple-features_base_3.png
│   ├── simple-features_contour_base_1.jpg
│   ├── simple-features_contour_base_2.jpg
│   └── simple-features_contour_base_3.jpg
├── output/
│   ├── simple-features_base_1_rotate.png
│   ├── simple-features_base_1_flip.png
│   ├── simple-features_base_1_blur.png
│   └── (other processed outputs)
└── README.md
```

---

## Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/RichieGarafola/ImageTransformations_ContourDetection.git
cd ImageTransformations_ContourDetection
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install opencv-python
```

3. **Run the notebook:**

```bash
jupyter notebook ImageTransformations_ContourDetection.ipynb
```

---

## Techniques Demonstrated

### Geometric Transformations
- **Rotation**: Adjust orientation using OpenCV’s `cv2.getRotationMatrix2D`
- **Flipping**: Mirror images horizontally/vertically
- **Blurring**: Reduce noise with Gaussian blur

### Contour Detection
- Convert to grayscale and binary
- Detect edges and contours with `cv2.findContours`
- Visualize and annotate objects with bounding rectangles and overlays

---

## Sample Output

| Transformation         | Preview                    |
|------------------------|----------------------------|
| Rotated Image          | ![](output/simple-features_base_1_rotate.png) |
| Flipped Image          | ![](output/simple-features_base_1_flip.png)   |
| Contour Detection      | ![](output/sample_contour_output.png)         |

---

## Learning Objectives

- Understand geometric image manipulation in OpenCV
- Extract visual structure using contour analysis
- Practice image pre-processing and visual augmentation
- Apply OpenCV's shape and feature extraction APIs

---

## Acknowledgements

- Developed for **CSC‑FPX4040** at Capella University
- Images and shapes created or sourced for academic analysis

---

## License

This project is for educational use only.  
Attribution is appreciated if reused or referenced.

---
