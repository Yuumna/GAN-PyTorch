# GAN-PyTorch
## Incremental implementation of Generative Adversarial Networks using PyTorch for MNIST dataset. 
### There are four implemetations: 
1. A GAN with linear layers only. 
2. A GAN with linear layers and batch normalization 
3. A GAN with 2D CNN layers and 2D Batch Normalization
4. A GAN with 2D CNN layers and Spectral Normalization


***
### Results

All models have been trained for the same number of epochs (50) to compare the differences between the four techniques.

|Vanilla GAN|GAN and BN|DCGAN|DCGAN+Spetral Norm.|
|-----------|----------|-----|-------------------|
|![image](https://user-images.githubusercontent.com/23558845/140943068-a9a3dd46-4917-4f48-a28c-e8bf53c00fc3.png)|![image](https://user-images.githubusercontent.com/23558845/140943534-20e9679a-b197-4a1d-89f3-21ccd23711bc.png)|![image](https://user-images.githubusercontent.com/23558845/140943928-2cfe7bae-0e10-4d83-9b04-d0b21804e7a5.png)|![image](https://user-images.githubusercontent.com/23558845/140944061-fe817092-22bd-45a6-a850-fc34adb21e86.png)|
|![image](https://user-images.githubusercontent.com/23558845/140943334-cde33cf4-a83c-45ed-b53e-598dceac3067.png)|![image](https://user-images.githubusercontent.com/23558845/140943602-e469e08f-bdcc-4557-a863-1e5d811fd717.png)|![image](https://user-images.githubusercontent.com/23558845/140943994-5f83f174-179c-49a9-9e41-de0c02530a8b.png)|![image](https://user-images.githubusercontent.com/23558845/140944082-8a469538-d3c4-401d-b0a7-4d117d3d624a.png)|


