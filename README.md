# CGAN on MNIST (DCGAN Architecture)

A Conditional Generative Adversarial Network (CGAN) built using the DCGAN architecture to generate handwritten digits from the MNIST dataset conditioned on class labels.

## How It Works
- **Generator**: Creates fake MNIST images based on random noise + labels.
- **Discriminator**: Classifies images as real or fake, using both image and label.
- Trained alternately to improve both networks in an adversarial loop.

## Requirements
```bash
pip install torch torchvision matplotlib numpy
Run
git clone https://github.com/<your-username>/cgan-mnist-dcgan.git
cd cgan-mnist-dcgan
python train.py


