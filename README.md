# Deep Image Prior with U-Net and Hourglass Networks

This project demonstrates the use of **Deep Image Prior (DIP)** for image reconstruction using U-Net and Hourglass-based architectures. The DIP framework reconstructs images from scratch using random noise as input, showcasing the ability of convolutional neural networks (CNNs) to learn structural patterns without explicit training data.

## Features

1. **U-Net with Skip Connections**:
   - A U-Net style architecture with skip connections for improved image reconstruction.
   - Demonstrates reconstruction of:
     - Original Image
     - Noisy Image
     - Scrambled Image
     - White Noise

2. **Hourglass Networks**:
   - Different configurations:
     - **1-layer Hourglass**
     - **3-layer Hourglass**
     - **5-layer Hourglass**
     - **5-layer Hourglass with Skip Connections**
     - **5-layer Hourglass with Skip Connections (Nearest Upsample)**
   - Visualizes structural patterns emerging from random noise.
