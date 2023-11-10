# Similarity-Calculation-between-Images

This Python script performs a structural similarity comparison between two images using the Structural Similarity Index (SSIM). The SSIM is a metric that quantifies the similarity between two images, considering luminance, contrast, and structure. The script utilizes the OpenCV (cv2) and scikit-image (skimage) libraries for image processing and SSIM calculation.

Requirements
Python 3.x
OpenCV (cv2): Used for image processing and resizing.
scikit-image (skimage): Provides the structural_similarity function for SSIM calculation.
Install the required packages using the following command:

pip install opencv-python scikit-image

Replace the following variables in the script:

image_path1: Path to the first image.
image_path2: Path to the second image.
target_width: Common width for resizing.
target_height: Common height for resizing.

image_path1 = "path/to/your/image1.jpg"
image_path2 = "path/to/your/image2.jpg"
target_width = 128
target_height = 128

The script will print the SSIM similarity between the two images.

