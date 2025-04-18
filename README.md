# 🚧 Road Segmentation of Chagda Road

This Digital Image Processing (DIP) project focuses on segmenting road areas from images of Chagda Road using Python and OpenCV.

## 📌 Objectives
- Segment roads using HSV color masking
- Apply image preprocessing and noise removal
- Remove small non-road regions using connected components
- Provide a PyQt5-based GUI for visualization

## 🧠 Methodology
1. Convert image to HSV and apply threshold to isolate road-like colors.
2. Erode mask to reduce noise and disconnect irrelevant regions.
3. Remove small connected components to refine road mask.
4. Apply mask on original image to extract the segmented road.
5. Visualize original, mask stages, and result in GUI.

## 💻 Technologies
- Python
- OpenCV
- PyQt5
- NumPy
- Matplotlib

## 🖼️ GUI Features
- Upload any image
- Automatically displays:
  - Original Image
  - HSV Mask
  - Eroded Mask
  - Final Mask
  - Segmented Road Image

## 👥 Team
- Gulraiz Nazir (NIM-BSEE-2021-01)
- Khurram Shehzad (NIM-BSEE-2021-20)

## 📅 Date
January 12, 2025

## 🧑‍🏫 Instructor
- Zulaikha Kiran  
- Lab Engineer: Junaid Ashraf
