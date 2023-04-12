# CNN-PyTorch
PyTorch Convolutional Neural Network Example

This is a simple example of a convolutional neural network (CNN) implemented using PyTorch. The network is trained on the CIFAR-10 dataset, which consists of 50,000 32x32 color images in 10 classes.
Getting Started

To run the code, you will need to have PyTorch and torchvision installed on your system. You can install them using pip:

pip install torch torchvision

Once you have PyTorch and torchvision installed, you can clone this repository and run the cnn.py script:

bash

git clone https://github.com/your-username/pytorch-cnn-example.git
cd pytorch-cnn-example
python cnn.py

The script will train the CNN on the CIFAR-10 dataset for a few epochs and print the loss every 2000 iterations.
Files

    cnn.py: The main script that defines the CNN architecture, loads the CIFAR-10 dataset, trains the model, and saves the trained weights to a file.
    data/: Directory containing the CIFAR-10 dataset. If the dataset is not present, it will be automatically downloaded when you run the script.
    weights.pth: The trained weights of the CNN, saved to a file after training.

Acknowledgements

The code is based on the PyTorch CNN tutorial available at https://pytorch.org/tutorials/. The CIFAR-10 dataset is provided by the Canadian Institute for Advanced Research (CIFAR).
