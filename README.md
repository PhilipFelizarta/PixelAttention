# PixelAttention
This post contains my research on using multi-head scaled dot-product attention in place of convolutions.

My focus with this project is to attain equivalent or better results on CIFAR10/100 using attention as the main mechanism for learning (1x1 2D convolutions become necessary to alter the dimensions of each pixel). Tools like Layca are used to save time fine-tuning regularization parameters.
