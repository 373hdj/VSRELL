# 🚀🚀🚀VSRELL-CVPR2026 The First CNN-Based Method for Joint Low-Light Enhancement and Video Super-Resolution
🚀🚀🚀CVPR 2026 | The First CNN-Based Method for Joint Low-Light Enhancement and Video Super-Resolution
[![CVPR 2026](https://img.shields.io/badge/CVPR-2026-ff4081?style=for-the-badge)](https://cvpr.thecvf.com/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.13+-orange?style=for-the-badge&logo=pytorch)](https://pytorch.org/)
[![GitHub Stars](https://img.shields.io/github/stars/373hdj/VSRELL?style=for-the-badge&color=yellow)](https://github.com/373hdj/VSRELL)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

🚀🚀🚀For more detailed visual effects, please refer to our website！
https://aughtty.github.io/vsrell-page/

**  Title--VSRELL: A Simple Baseline for Video Super-Resolution and Enhancement in Low-Light Environment**
> The first CNN-based end-to-end framework to jointly solve Low-Light Enhancement (LLE) and Video Super-Resolution (VSR), breaking the multi-degradation coupling bottleneck in low-light video restoration with SOTA performance, lightweight design and strong temporal consistency.

### 🎯 Core Highlight
Address the pain points of **error accumulation, parameter redundancy and poor temporal consistency** in traditional cascaded/all-in-one methods for low-light video restoration. We propose a novel integrated learning scheme that jointly models illumination enhancement and spatial-temporal super-resolution, realizing synchronous decoupling of low-light and low-resolution degradations to recover **Well-Illuminated High-Resolution (WIHR)** video sequences from **Low-Light Low-Resolution (LLLR)** inputs.
-<img width="741" height="436" alt="image" src="https://github.com/user-attachments/assets/ab7df027-f30d-4097-b576-5bcdf1c9e190" />


### 📊 SOTA Results
VSRELL achieves **25.94 average PSNR** and **0.7813 average SSIM** on REDS4, with over 6dB PSNR gain compared to mainstream all-in-one methods, and significant advantages in qualitative visual effect, temporal consistency and generalization ability.
- **Quantitative**: Leading PSNR/SSIM on all test datasets (REDS4/Vid4/UDM10)
- **Qualitative**: Clear detail restoration, natural brightness enhancement, no color cast/frame flickering
- **Efficiency**: Far fewer parameters and faster inference than SOTA comparative methods
<img width="737" height="192" alt="image" src="https://github.com/user-attachments/assets/14aab477-bde3-4b58-a8b2-98bf94e791ff" />
<img width="742" height="580" alt="image" src="https://github.com/user-attachments/assets/bc95be3c-bb80-4c44-9de3-6270d6013219" />



### 👨‍🔬 Authors
Yanming Hui¹,², **Fanhua Shang¹,²\***, **Hongying Liu²,⁴\***, Ben Wang¹,², Zhenwei Zhang¹,², **Liang Wan²,³\***, Wei Feng¹,², Tong Xue¹,², Bingqin Lv¹,²
1. School of Computer Science and Technology, Tianjin University, China
2. The Key Research Center for Surface Monitoring and Analysis of Relics, SMARC
3. School of Computer Software, Tianjin University, China
4. Medical School, Tianjin University, China
\*Corresponding Authors

### 📑 Citation
```bibtex
@inproceedings{hui2026vsrell,
  title={VSRELL: A Simple Baseline for Video Super-Resolution and Enhancement in Low-Light Environment},
  author={Hui, Yanming and Shang, Fanhua and Liu, Hongying and Wang, Ben and Zhang, Zhenwei and Wan, Liang and Feng, Wei and Xue, Tong and Lv, Bingqin},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}
```

### 📧 Contact
- Yanming Hui: ymhui@tju.edu.cn
- Corresponding Author: Fanhua Shang (fhshang@tju.edu.cn)

### ⚡ Quick Access
- **Paper**: [Coming Soon]
- **Code & Pre-trained Models**: This Repository [Coming Soon]
- **Dataset**: REDS/Vid4/UDM10 (low-light processed)

---
**LLLR → WIHR | One CNN, Two Tasks | SOTA Low-Light Video Restoration** 🚀

