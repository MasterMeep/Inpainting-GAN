# Inpainting-GAN
based off https://arxiv.org/pdf/1604.07379.pdf
paints in the masked out portions of images with relatively good accuracy. its a DCGAN network that uses a combination of adversarial (BCE) and reconstruction loss (L1), and is trained on the CelebA dataset for ~10 epochs
