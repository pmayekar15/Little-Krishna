# little_krishna

# Neon Sketch Reveal

A Python script that generates a dynamic neon particle and edge-sketch reveal animation from an image using OpenCV and NumPy.

## How it Works

1. Computes an edge mask from the input image and applies a multi-pass Gaussian blur glow filter.
2. Downsamples the glow layer into a mosaic grid and reveals circular blocks in random order.
3. Iteratively shrinks the block size to refine the mosaic into sharp neon sketch lines.
4. Smoothly crossfades from the neon edge sketch into the original image.
5. Adds a bottom vertical mirror gradient for a floor reflection effect.

## Requirements

- Python 3.8+
- OpenCV
- NumPy

Install the dependencies:

```bash
pip install opencv-python numpy
