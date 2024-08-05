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
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use: env\Scripts\activate
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

    Ensure `requirements.txt` includes packages such as `numpy`, `scipy`, `opencv-python`, `matplotlib`, etc. You can create it using:

    ```bash
    pip freeze > requirements.txt
    ```

## Usage

### Run FFT Algorithms

To execute a specific FFT algorithm, navigate to the `fft_algorithms/` directory and run the script corresponding to the desired algorithm. For example:

```bash
python cooley_tukey_fft.py
