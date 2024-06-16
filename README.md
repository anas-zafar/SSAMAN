# SSAMAN: Single Stage Adaptive Multi-Attention Network for Image Restoration
The official pytorch implementation of the paper **[Single Stage Adaptive Multi-Attention Network for Image Restoration](https://ieeexplore.ieee.org/abstract/document/10495777)**

>Recently attention-based networks have been successful for image restoration tasks. However, existing methods are either computationally expensive or have limited receptive fields, adding constraints to the model. They are also less resilient in spatial and contextual aspects and lack pixel-to-pixel correspondence, which may degrade feature representations. In this paper, we propose a novel and computationally efficient architecture Single Stage Adaptive Multi-Attention Network (SSAMAN) for image restoration tasks, particularly for image denoising and image deblurring. SSAMAN efficiently addresses computational challenges and expands receptive fields, enhancing robustness in spatial and contextual feature representation. Its Adaptive Multi-Attention Module (AMAM), which consists of Adaptive Pixel Attention Branch (APAB) and an Adaptive Channel Attention Branch (ACAB), uniquely integrates channel and pixel-wise dimensions, significantly improving sensitivity to edges, shapes, and textures. We perform extensive experiments and ablation studies to validate the performance of SSAMAN. Our model shows state-of-the-art results on various benchmarks, for example, on image denoising tasks, SSAMAN achieves a notable 40.08 dB PSNR on SIDD dataset, outperforming Restormer by 0.06 dB PSNR, with 41.02% less computational cost, and achieves a 40.05 dB PSNR on the DND dataset. For image deblurring, SSAMAN achieves 33.53 dB PSNR on GoPro dataset.



## Installation
git clone https://github.com/anas-zafar/SSAMAN
cd SSAMAN
pip install -r requirements.txt

### Citations
```
@article{zafar2024single,
  title={Single Stage Adaptive Multi-Attention Network for Image Restoration},
  author={Zafar, Anas and Aftab, Danyal and Qureshi, Rizwan and Fan, Xinqi and Chen, Pingjun and Wu, Jia and Ali, Hazrat and Nawaz, Shah and Khan, Sheheryar and Shah, Mubarak},
  journal={IEEE Transactions on Image Processing},
  year={2024},
  publisher={IEEE}
}
```
