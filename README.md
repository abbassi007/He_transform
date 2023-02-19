# He_transform_for_JPEG-AI
## Short description
In this study, we propose a new approach of hierarchical error (He) transform in order to improve the performance of end-to-end learned-based image compression. We extend the previous existing model (Balle) of learned-based image compression and follow their work with the proposed approach of He transform. Based on the experimental results, our proposed method outperforms in terms of the peak signal to noise ratio (PSNR) with both the Y and YUV components of the image (PSNR-Y and PSNR-YUV) over the conventional codecs of the Joint Photographic Experts Group (JPEG), which saves 39.42% of the bit per pixel (bpp) in the PSNR-Y and 40.10% of the bpp in the PSNR-YUV, and with JPEG200, which saves 27.21% of the bpp in the PSNR-Y and 25.93% of the bpp in the PSNR-YUV, for the mean square error (MSE) optimize model. In addition, our method also outperforms High Efficiency Video Coding (HEVC) in the MS-SSIM quality metric, which saves 39.08% of the bpp, for the multi-scale structure (MS-SSIM) optimized model.
## Architecture
![](https://github.com/abbassi007/He_transform_for_JPEG-AI/blob/master/Framework.png)
## Experimental Setup
### Evaluation Procedure & Matrices
![](https://github.com/abbassi007/He_transform_for_JPEG-AI/blob/master/Evaluation%20procedure.jpg)
### Results
#### MSE optimized model
![](https://github.com/abbassi007/He_transform_for_JPEG-AI/blob/master/MSE%20optimized%20model%20results_.png)
![](https://github.com/abbassi007/He_transform_for_JPEG-AI/blob/master/MSE%20optimized%20model%20results.png)
#### MS-SSIM optimized model
![](https://github.com/abbassi007/He_transform_for_JPEG-AI/blob/master/MS-SSIM%20optimized%20model%20results.png)
![](https://github.com/abbassi007/He_transform_for_JPEG-AI/blob/master/Visualization.png)
