# Blue M&M Counter

This project utilizes OpenCV and Python to develop a program that can identify and count the number of blue M&M candies in a given set of images. The program outputs the processed images with blue M&Ms circled in magenta and all other M&Ms circled in green. Additionally, it provides a tuple containing the total count of M&Ms and the count of orange M&Ms for each image.

## Installation

To run the program, make sure you have the following dependencies installed:

- Python (version 3.6 or higher)
- OpenCV (version 4.0 or higher)
- NumPy (version 1.19 or higher)

You can install the necessary packages using pip, the Python package manager. Open your terminal and run the following command:

```
pip install opencv-python numpy
```

## Usage

1. Clone this repository to your local machine or download the source code files.

2. Place the images you want to process in the same directory as the project files.

3. Open a terminal and navigate to the project directory.

4. Run the following command:

   ````
   python blue_mms_counter.py
   ```

   The program will process all the images in the directory and generate the processed images with the blue M&Ms circled in magenta.

   The program will also display the total count of M&Ms and the count of orange M&Ms for each image in the terminal.

5. Check the output directory for the processed images. The images will be saved with the prefix "processed_" followed by the original image filename.

## Customization

You can modify the program to suit your specific needs. Here are some possible customizations:

- **Input Directory:** By default, the program processes all the images in the same directory as the project files. If you want to process images from a different directory, you can modify the code in `blue_mms_counter.py` by providing the path to the input directory.

- **Output Directory:** The processed images are saved in the `output` directory by default. If you want to change the output directory, you can modify the code in `blue_mms_counter.py` by providing the desired path.

- **Circle Colors:** If you prefer different colors for the circles around the blue and non-blue M&Ms, you can modify the code in `blue_mms_counter.py` by changing the values of `BLUE_COLOR` and `GREEN_COLOR` variables respectively. You can specify the colors using the BGR format (e.g., `(255, 0, 0)` for blue).

## Contributing

If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request on the GitHub repository for this project.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

---
Note: This README assumes that you have a basic understanding of Python and using OpenCV. If you need further assistance, please refer to the official documentation of OpenCV or consult relevant resources.
