# Neural Style Transfer

Neural Style Transfer is a sophisticated deep learning technique that enables the seamless application of artistic styles from one image to another. This repository provides a user-friendly implementation with pre-trained models and the ability to create new models using custom datasets.

## Usage

To stylize an image, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/neural-style-transfer.git
    cd neural-style-transfer
    ```

2. Execute the following command:

    ```bash
    transform("udnie.pth", "input.jpg")
    ```

    Replace `udnie.pth` with the desired pre-trained model (options: candy, udnie, mosaic, rain_princess), `input.jpg` with the input image filename, and `output.jpg` with the desired output filename.

## Pre-trained Models

The repository includes pre-trained models for the following styles:

- `candy.pth`
- `udnie.pth`
- `mosaic.pth`
- `rain_princess.pth`

## Creating New Models

Custom models can be created by training on user-defined datasets. Refer to the documentation for comprehensive instructions on training new models.

## Dependencies

Ensure the following dependencies are installed:

- Python 3
- PyTorch
- torchvision
- Pillow
- matplotlib

Install dependencies using:

```bash
pip install -r requirements.txt

