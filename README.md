# Vision Transformer for Image Classification

This project implements a Vision Transformer (ViT) model for image classification on the CIFAR-10 dataset. The ViT model, originally designed for natural language processing, has shown promising results in computer vision tasks.

## Requirements

- TensorFlow
- TensorFlow Addons
- NumPy
- Matplotlib

## Usage

1. **Install the required libraries:**
2. **Run the code:**
   ## Model Architecture

The ViT model consists of the following components:

- **Patch Extraction:** Images are divided into fixed-size patches.
- **Patch Encoding:** Each patch is linearly embedded and augmented with positional information.
- **Transformer Layers:** Multiple transformer layers capture global dependencies between patches.
- **MLP Head:** A multi-layer perceptron (MLP) maps the transformer output to class probabilities.

## Results

The trained ViT model achieves competitive accuracy and top-5 accuracy on the CIFAR-10 test dataset.

## Conclusion

This project demonstrates the effectiveness of Vision Transformers for image classification and provides a starting point for further exploration and optimization.
