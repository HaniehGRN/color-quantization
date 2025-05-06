# Color Quantization Using K-Means Clustering

## Overview

This project implements color quantization on images using the K-Means clustering algorithm. It reduces the number of distinct colors in an image by clustering similar colors and replacing them with the cluster centers, effectively compressing the image while preserving its visual appearance.

## Features

- Loads an input image
- Reshapes the image into pixel data suitable for clustering
- Applies K-Means clustering to group colors into 3 clusters
- Replaces each pixel's color with its corresponding cluster center
- Displays the original and quantized images side by side for comparison

<img src="./README/color-quantization.jpg" alt="Palm trees color quantization" width="450" /><br>

## Requirements

- Python 3.x
- NumPy
- Matplotlib

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HaniehGRN/color-quantization.git
   cd color-quantization
   ```

2. Install the required packages:
   ```bash
   pip install opencv-python numpy matplotlib
   ```

## Usage

Run the `color-quantization.py` script with the path to your image:

```bash
python color-quantization.py path_to_image.jpg
```

The script will display the original and quantized images side by side.

## License

This project is licensed under the MIT License.
