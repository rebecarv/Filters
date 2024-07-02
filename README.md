# Filters
This C program applies various filters to images. It supports greyscale, sepia, horizontal reflection, and blur filters. The program takes an input image, applies the selected filter, and saves the output image.

Features
* Greyscale: Converts the image to shades of grey.
* Sepia: Applies a sepia tone to the image.
* Reflect: Reflects the image horizontally.
* Blur: Applies a blur effect to the image.

Usage
To apply a filter to an image, run the program with the following syntax:
./filter [option] input_image output_image

* [option]: The filter to apply. Options are:
 * -g for greyscale
 * -s for sepia
 * -r for reflection
 * -b for blur
 * input_image: The path to the input image file.
 * output_image: The path where the output image will be saved.

   
Example:
Apply a greyscale filter to yard.bmp and save the result as out.bmp:
./filter -g images/yard.bmp out.bmp
