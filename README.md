# Mathematical Transforms Using Image Analysis

## Overview

This repository explores various Fast Fourier Transform (FFT) algorithms and their application in image analysis. It includes implementations of different FFT algorithms, such as Cooley-Tukey, Rader-Brenner, Bruun’s, and Winograd algorithms, along with an examination of Ramanujan Fourier Transforms. The primary focus is on the theoretical and practical aspects of these transforms and their effectiveness in image compression.

## Contents

- `fft_algorithms/` - Contains implementations of different FFT algorithms.
- `image_analysis/` - Includes scripts for image analysis and compression using FFT.
- `ramanujan_transform/` - Contains implementations related to the Ramanujan Fourier Transform.

## Installation

To run the code, you need to set up your environment with the necessary dependencies. This project uses Python and requires several packages. Follow these steps to set up the environment:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   cd your-repository-name
## Create and activate a virtual environment:

bash
Copy code
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
Install the required packages:

bash
Copy code
pip install -r requirements.txt

## Ensure requirements.txt includes packages such as numpy, scipy, opencv-python, matplotlib, etc. You can create it using:

bash
Copy code
pip freeze > requirements.txt
Usage
Run FFT Algorithms:

## To execute a specific FFT algorithm, navigate to the fft_algorithms/ directory and run the script corresponding to the desired algorithm. For example:

bash
Copy code
python cooley_tukey_fft.py
Perform Image Analysis:

## For image analysis using FFT, go to the image_analysis/ directory. To compress an image using FFT, run:

bash
Copy code
python image_compression.py --input path/to/image.jpg --output path/to/output.jpg --compression-value C
Replace path/to/image.jpg with the path to your input image, path/to/output.jpg with the desired output path, and C with the compression value.

## Run Ramanujan Transform:

To run the Ramanujan Fourier Transform, navigate to the ramanujan_transform/ directory and execute:

bash
Copy code
python ramanujan_transform.py --input path/to/image.jpg --output path/to/output.jpg
Adjust the paths as needed for your input and output files.

Contributing
Contributions are welcome! To contribute to this project, follow these steps:

## Fork the repository:

Click the "Fork" button at the top-right of the repository page on GitHub.

##Clone your fork:

bash
Copy code
git clone https://github.com/yourusername/your-repository-name.git

## Create a new branch:

bash
Copy code
git checkout -b your-branch-name

##Make your changes and commit:

bash
Copy code
git add .
git commit -m "Add a descriptive message about your changes"
Push your changes:

bash
Copy code
git push origin your-branch-name
Create a pull request:

Go to your repository on GitHub and click the "Compare & pull request" button. Describe your changes and submit the pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## References
Fourier Transform - Wikipedia
Image Compression Based on 2D Discrete Fourier Transform
Cooley-Tukey FFT Algorithm
Winograd’s Short DFT Algorithms
Ramanujan Computing Technology
Congruences mod Primes, Order, Primitive Roots
Srinivasa Ramanujan and Signal Processing Problems
