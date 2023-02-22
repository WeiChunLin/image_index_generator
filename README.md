# Image Index Generator

The `image_index_cal` function calculates the image quality index for all images in the given directory and saves the results as a CSV file. This function uses the OpenCV library to read the images, and calculates the quality index by analyzing the intensity ratio and texture smoothness ratio of the images.


```python
image_index_cal(directory)
```
* `directory (required)`: The directory containing the images.

This will calculate the quality index for all images in the given directory and save the results as a CSV file named "Image_quality_table.csv" in the same directory.

# Exceptions
* ValueError: If the input directory is not a valid directory or does not contain any images.

# Requirements
This function requires the following Python libraries to be installed:

* OpenCV
* NumPy
* Pandas

# Output
The output of the `image_index_cal` function is a CSV file named "Image_quality_table.csv" that contains the file names and quality index values for all images in the given directory.

# License
This function is released under the MIT License.
