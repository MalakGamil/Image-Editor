This program is a comprehensive grayscale image processing tool designed for the FCAI OOP Programming Assignment 1, 2023. It allows users to apply various filters and transformations to grayscale images. Key features include:

    Image Operations:
        Load and Save: Users can load images and save modifications.
        Black & White Filter: Converts images to black and white based on pixel intensity average.
        Invert Colors: Inverts pixel values to create a negative effect.
        Merge Images: Combines two images by averaging pixel values.
        Flip Image: Horizontally or vertically flips the image.
        Rotate Image: Rotates the image by 90°, 180°, or 270° clockwise.
        Darken/Lighten: Adjusts image brightness by 50%.
        Edge Detection: Identifies edges using the Sobel operator.

    User Interaction:
        A menu-driven interface guides users to apply filters or transformations.
        Users can save modifications or continue applying additional filters.

    Implementation:
        Includes a variety of functions for image processing, all working on a 2D image array.
        Utilizes external functions from the bmplib.cpp library for handling BMP files.
        Efficiently manages temporary arrays and memory for pixel manipulation.

The program aims to enhance users' understanding of object-oriented programming concepts and image processing while providing practical functionality for grayscale image editing.
