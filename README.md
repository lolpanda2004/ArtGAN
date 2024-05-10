# Abstract Art by GAN

This project is an implementation of a Generative Adversarial Network (GAN) to generate abstract art. GANs are a class of machine learning models that consist of two neural networks, a generator and a discriminator, which are trained simultaneously. The generator learns to generate new data samples that are similar to a training dataset, while the discriminator learns to distinguish between real and generated data.

## Features

- Abstract Art Generation: The GAN model is trained on a dataset of abstract art images to learn the underlying patterns and styles. Once trained, it can generate new abstract art pieces that resemble the training data.
- Customizable Parameters: The project allows users to customize various parameters of the GAN model, such as the number of training epochs, learning rates, and network architectures, to experiment with different configurations and achieve desired results.

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- (Optional) CUDA-compatible GPU for faster training (recommended for large datasets and complex models)

## Usage
1. Clone the repository:
git clone https://github.com/your_username/abstract-art-gan.git
cd abstract-art-gan

2. Install the required dependencies:
pip install -r requirements.txt

3. Prepare your dataset of abstract art images. Ensure that the images are preprocessed and stored in a suitable format (e.g., JPEG or PNG).

4. Modify the configuration settings in config.py according to your preferences, such as the paths to the dataset and the desired hyperparameters for training.

5.Train the GAN model:
python train.py

6. Once training is complete, generate new abstract art:
python generate.py

## Input
![Input](https://github.com/lolpanda2004/ArtGAN/assets/98698654/b52b4282-6d8f-4e78-bbaf-474d6056ccf0)

## Output
![Output](https://github.com/lolpanda2004/ArtGAN/assets/98698654/04071c2b-4c04-43b2-b960-2ac9de22be2a)



