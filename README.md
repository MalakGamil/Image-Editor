# Grayscale Image Processing Tool

This program is a comprehensive grayscale image processing tool developed for the FCAI OOP Programming Assignment 1, 2023. It enables users to apply various filters and transformations to grayscale images.

## Key Features:

### Image Operations:
- **Load and Save**: Users can load grayscale images and save modifications.
- **Black & White Filter**: Converts images to black and white based on the average pixel intensity.
- **Invert Colors**: Inverts pixel values to create a negative effect.
- **Merge Images**: Combines two images by averaging pixel values.
- **Flip Image**: Allows horizontal or vertical flipping of the image.
- **Rotate Image**: Rotates the image by 90°, 180°, or 270° clockwise.
- **Darken/Lighten**: Adjusts image brightness by 50%.
- **Edge Detection**: Identifies edges using the Sobel operator.

### User Interaction:
- **Menu-driven Interface**: A user-friendly menu guides users through applying filters or transformations.
- **Save or Continue**: Users can save their modifications or continue applying additional filters.

### Implementation:
- The program includes various functions for image processing, all working on a 2D array representation of the image.
- It utilizes external functions from the `bmplib.cpp` library for handling BMP files.
- Efficient memory management and temporary arrays are used to handle pixel manipulations.

This program aims to deepen the understanding of object-oriented programming (OOP) principles while providing practical functionality for editing grayscale images.
