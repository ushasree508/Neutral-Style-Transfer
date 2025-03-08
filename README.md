# Neural Style Transfer (NST)

## Introduction
Neural Style Transfer (NST) is a deep learning technique that applies the artistic style of one image (the "style image") to the content of another image (the "content image"). This is achieved using Convolutional Neural Networks (CNNs), typically leveraging pre-trained models such as VGG19.

## Features
- Extracts content and style representations using CNN layers.
- Combines content and style representations to create a new, stylized image.
- Uses optimization techniques like gradient descent to refine the generated image.
- Can be implemented using frameworks such as TensorFlow or PyTorch.

## Prerequisites
Ensure you have the following installed:
- Python (>=3.7)
- TensorFlow or PyTorch
- NumPy
- Matplotlib
- PIL (Pillow)

To install dependencies, use:
```bash
pip install tensorflow numpy matplotlib pillow
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/neural-style-transfer.git
   cd neural-style-transfer
   ```
2. Place your content and style images in the `images/` directory.
3. Run the script:
   ```bash
   python style_transfer.py --content images/content.jpg --style images/style.jpg --output images/output.jpg
   ```
4. View the generated image in the `images/` folder.

## How It Works
1. **Feature Extraction**: Extracts content and style features using CNN layers.
2. **Content Loss**: Ensures the generated image maintains the structure of the content image.
3. **Style Loss**: Encourages the generated image to adopt the artistic patterns of the style image.
4. **Optimization**: Uses gradient descent to minimize content and style losses iteratively.

COMPANY: CODTECH IT SOLUTIONS

NAME: ORSU USHA SREE

INTERN ID:CT08TMH

DOMAIN:ARTIFICIAL INTELLIGENCE

DURATION:4WEEKS

MENTOR:NEELA SANTOSH ##OUTPUT

![Screenshot (16)](https://github.com/user-attachments/assets/6bee8e11-d2f7-44c5-a9b2-d1cdbd6dfd33)




