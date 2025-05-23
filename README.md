# 🎨 Chromatix-GAN: Image Colorization with UNet & GAN

**End-to-end deep learning system for automatic grayscale-to-color image translation using adversarial training**

## 📌 Overview
This project implements:
- **Hybrid UNet-GAN Architecture**:
  - UNet generator for precise pixel-to-pixel color mapping
  - PatchGAN discriminator for realistic texture generation
- **Lab Color Space Optimization**: Focuses on ab channels for vibrant results
- **Perceptual Loss**: Combines adversarial, L1, and VGG-based losses

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/yourusername/Chromatix-GAN.git
cd Chromatix-GAN
pip install -r requirements.txt  # torch, opencv, pillow
