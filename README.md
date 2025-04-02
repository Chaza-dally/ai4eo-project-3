# **Satellite Image Compositing**

## **Overview**
This project focuses on seamlessly compositing multiple satellite images into a single high-quality image using advanced image processing techniques. The goal is to ensure smooth transitions between overlapping images while maintaining color consistency and preserving geographic details.

### **Key Features**
- **Histogram Matching:** Adjusts color balance across images for consistency.
- **Feathering-Based Blending:** Reduces sharp seams using soft transitions.
- **Pyramid Blending:** Ensures seamless merging using Gaussian and Laplacian pyramids.
- **Edge Smoothness Analysis:** Evaluates blending quality using the Laplacian variance method.
- **Automatic Color Adjustment:** Enhances visual quality with Contrast Limited Adaptive Histogram Equalization (CLAHE).

## **Installation**
### **Requirements**
Ensure you have Python installed along with the following dependencies:
```bash
pip install numpy opencv-python matplotlib
```

## **Usage**
### **Step 1: Prepare Images**
Place your satellite images in the `images/` directory.

### **Step 2: Run the Compositing Script**
Run the main Python script to process and blend the images:
```bash
python main.py
```

### **Step 3: View Results**
The final composited image will be saved in the `output/` directory.

## **File Structure**
```
project-folder/
│── images/        
    │── output/    # Folder for saving composited images
    │── input/     # Folder for input satellite images
│── main.py        # Main script for processing images
│── script.py    # Contains blending functions
│── README.md      # Project documentation
```

## **Future Enhancements**
- **Deep Learning Integration:** Implement CNN-based compositing for more adaptive blending.
- **Multi-Spectral Image Support:** Extend functionality to process different satellite bands.
- **Real-Time Processing:** Optimize algorithms for faster execution in large-scale applications.
- **Automatic Geometric Alignment:** Use AI-driven registration techniques for precise alignment.
- **Adaptive Blending Strategies:** Adjust blending techniques based on image texture and brightness.
- **Noise Reduction and Super-Resolution:** Enhance image clarity using AI-based denoising and upscaling.
- **GIS and Remote Sensing Integration:** Develop compatibility with ArcGIS, QGIS, and Google Earth Engine.
- **User-Friendly Interface:** Create a GUI to simplify processing for non-expert users.

## **License**
This project is licensed under the MIT License. See `LICENSE` for details.

## **Contributors**
- Chaza Dally, Youssef Dawoud, Jinane Al Ammar


## **Contact**
For inquiries or contributions, feel free to reach out via email or open an issue on the repository.

---
Happy coding! 🚀
