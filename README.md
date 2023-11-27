# Neural Style Transfer with Keras

## Overview

This repository contains an implementation of Neural Style Transfer using the Keras library. The project utilizes the VGG19 model for feature extraction and L-BFGS optimization for generating stylized images.

## Contents

- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Results](#results)
- 
## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- Keras
- SciPy
- NumPy
- ImageIO

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
git clone https://github.com/your-username/neural-style-transfer.git
cd neural-style-transfer
python neural_style_transfer.py

/neural-style-transfer
  |-- neural_style_transfer.py
  |-- README.md
  |-- requirements.txt
  |-- /images
      |-- wallpaper.jpeg
      |-- images.jpeg
  |-- /results
      |-- my_result_at_iteration_0.png
      |-- my_result_at_iteration_1.png
      |-- ...



