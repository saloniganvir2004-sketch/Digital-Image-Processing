# Digital Image Processing

A Python-based implementation of fundamental digital image processing and image enhancement techniques.

## Implemented Techniques

1. Image Negative Transformation
2. Power-Law (Gamma) Transformation
3. Log Transformation

## Technologies Used

- Python
- NumPy
- OpenCV
- Matplotlib
- Pillow
- Google Colab

## Execution

1. Open the Jupyter notebook in Google Colab.
2. Upload an input image.
3. Execute the notebook cells sequentially.
4. Observe and compare the transformed images.

## Project Structure

```text
Digital-Image-Processing/
├── Image_Intensity_Transformations.ipynb
├── README.md
└── requirements.txt
### Step 2. Create requirements.txt

```bash
cat > requirements.txt <<'EOF'
numpy
opencv-python
matplotlib
Pillow

## Additional Implementation: Image Intensity Transformations

This notebook demonstrates three fundamental intensity transformation techniques using Python, OpenCV, and NumPy.

### Implemented Techniques

1. Negative Transformation
   - Converts colour images into grayscale.
   - Applies s = L - 1 - r.
   - Generates negative images.

2. Log Transformation
   - Applies logarithmic intensity transformation.
   - Uses s = c * log(1 + r).
   - Enhances details in darker intensity regions.

3. Power-Law Transformation
   - Implements gamma correction.
   - Uses gamma = 0.9.
   - Applies normalized pixel intensity transformation.

### Additional Features

- Upload multiple images using Google Colab.
- Access individual grayscale pixel values.
- Generate transformation matrices.
- Visualize original and transformed images.

Notebook: Image_Intensity_Transformations_Corel1000.ipynb


## Image Resizing and Interpolation Techniques

This notebook demonstrates image resizing and different interpolation techniques using Python and OpenCV.

### Implemented Techniques

1. Image Resizing
   - Resizes an input image from 512 × 512 to 256 × 256 pixels.
   - Displays original and resized image dimensions.

2. Nearest Neighbour Interpolation
   - Uses the nearest pixel value for resizing.

3. Bilinear Interpolation
   - Uses neighbouring pixel values to calculate interpolated pixels.

4. Bicubic Interpolation
   - Applies cubic interpolation for image resizing.

5. Lanczos Interpolation
   - Uses Lanczos interpolation for image resizing.

### Additional Features

- Upload images using Google Colab.
- Display original and resized images.
- Save the resized image as a JPG file.
- Generate resized images using four interpolation methods.

### Technologies Used

- Python
- OpenCV
- Google Colab

Notebook: Image_Resizing_Techniques.ipynb

