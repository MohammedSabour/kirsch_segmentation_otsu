# Closed Contour Detection


## 📂 Project Overview
The primary objective of this mini-project is to perform automatic segmentation of closed shapes. Unlike standard edge detectors (like Canny or Sobel), this approach uses the Kirsch compass masks to capture edges in eight different directions, ensuring robust detection of complex boundaries before applying Otsu's global thresholding for binarization.

## ⚙️ Technologies Used

- Python 🐍
- NumPy
- OpenCV (cv2)
- Matplotlib
- Pillow (PIL)

## 📌 Key Steps
- Load and convert images to grayscale.

- Apply Kirsch Compass Masks for multi-directional edge detection.

- Calculate the optimal threshold using Otsu’s Method.

- Binarize the image and filter for closed/convex contours .

- Visualize the step-by-step transformation from raw image to segmented mask.

## 📈 Results
 
- Optimal Threshold: Automatically calculated (e.g., 142).
- Segmentation: Successfully isolates closed objects while ignoring noise and broken lines.
- Visualization: Clear 4-pane plot showing the original, the edges, the binarized version, and the final result.

## 📸 Screenshots
This plot shows the transition from the original grayscale image to the final segmented closed contours. 

<img width="1990" height="363" alt="download" src="https://github.com/user-attachments/assets/b80ed8c5-f6be-4b96-9e50-f722938e9112" />







