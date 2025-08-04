# 🎨 Neural Style Transfer using CNN (VGG19)

This project performs neural style transfer using pretrained **VGG19** CNN.

---

## 📌 How to Run

1. Prepare two images:  
   - `content.jpg` (the content image)  
   - `style.jpg` (the style image)  

2. Run:

```bash
pip install tensorflow matplotlib
python style_transfer_cnn.py

Model Details
Uses VGG19 pretrained on ImageNet

Optimizes pixel values to combine content & style

Style layers: block1_conv1, block2_conv1, ..., block5_conv1

Content layer: block5_conv2

Optimization: Adam
