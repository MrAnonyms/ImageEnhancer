# ImageEnhancer
Deployment Link :
https://imageenhancercompvis.streamlit.app/

Description
This project is a Computer Vision course assignment that implements and compares two deep learning–based Single Image Super-Resolution (SISR) models: SRResNet and ESRGAN-Lite. Both models perform 4× image upscaling using the DIV2K dataset, with a focus on comparing objective reconstruction accuracy and perceptual image quality.

Objectives
    Implement SRResNet as a PSNR-oriented baseline model
    Implement a lightweight ESRGAN-Lite model for perceptual super-resolution
    Compare training behavior and visual output quality
    Deploy trained models using ONNX and Streamlit

Models
    SRResNet
        Residual CNN optimized using MAE (L1) loss
        Produces stable and smooth super-resolved images

    ESRGAN-Lite
        Lightweight RRDB-based architecture
        Uses perceptual loss (L1 + gradient + VGG)
        Produces sharper and more realistic textures

Technologies Used
    Python
    TensorFlow / Keras
    ONNX & ONNX Runtime
    Streamlit
    OpenCV, NumPy, Pillow

