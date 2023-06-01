---
layout: post
title:  "CUDA+CuDNN+TF_Setting"
date:   2023-05-23 22:22:00 +0900
categories: ML/DL LAB CUDA
---
<!--
&nbsp; - space letter
img path = ~/bandalcom.github.io/posts_img/CUDA+CuDNN+TF_Setting/
img scale
small - width="40%" height="30%"
large - width="60%" height="40%"
-->
The professor requests the installation of the CUDA environment on the server computer.  


***** 
1. Visual Studio  

2. Anaconda  

3. Device Specification 

4. CUDA and cuDNN  

5. TENSORFLOW  

6. PyTorch  
  

*****


# 1. Visual Studio

<img src="/posts_img/CUDA+CuDNN+TF_Setting/Compiler_IDE_Native.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="Compiler_IDE_Native">  

  

&nbsp;Visual Studio 2022 17.0 community product not found  

Uncertainty of higher version[ex)17.6] VScode stability and reliability  

Choose to install VScode 2019 community product instead.  

<img src="/posts_img/CUDA+CuDNN+TF_Setting/Visual_Studio_2019_installer_download.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="Visual_Studio_2019_installer_download">  

  

*****

# 2. Anaconda  

[https://www.anaconda.com/](https://www.anaconda.com/) 

<img src="/posts_img/CUDA+CuDNN+TF_Setting/Anaconda_installer_download.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="Anaconda_installer_download">

  

Installed with no specific changes

Anaconda Virtual Environment setting  

  

```

(base) PS C:\Users\ParkLab> conda create -n tf310 python=3.10

(base) PS C:\Users\ParkLab> conda activate tf310

(tf310) PS C:\Users\ParkLab>

```

  

*****
# 3. Device Specification

Device Manager >  

<img src="/posts_img/CUDA+CuDNN+TF_Setting/Device_Manager.jpg" width="60%" height="40%" title="px(픽셀) 크기 설정" alt="Device_Manager"> 


NVIDIA RTX A6000 (Quadro)  

  

*****
# 4. CUDA and CuDNN  

  

## NVIDIA Driver Download

  

[https://www.nvidia.com/Download/index.aspx?lang=kr](https://www.nvidia.com/Download/index.aspx?lang=kr)  

<img src="/posts_img/CUDA+CuDNN+TF_Setting/NVIDIA_driver_download_1.jpg" width="60%" height="40%" title="px(픽셀) 크기 설정" alt="NVIDIA_driver_download_1">

<img src="/posts_img/CUDA+CuDNN+TF_Setting/NVIDIA_driver_download_2.jpg" width="60%" height="40%" title="px(픽셀) 크기 설정" alt="NVIDIA_driver_download_2"> 

<img src="/posts_img/CUDA+CuDNN+TF_Setting/NVIDIA_driver_install_1.jpg" width="60%" height="40%" title="px(픽셀) 크기 설정" alt="NVIDIA_driver_install_1">

<img src="/posts_img/CUDA+CuDNN+TF_Setting/NVIDIA_driver_install_2.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="NVIDIA_driver_install_2">
<img src="/posts_img/CUDA+CuDNN+TF_Setting/NVIDIA_driver_install_3.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="NVIDIA_driver_install_3">

  
  

## CUDA - GPU match

[https://www.wikiwand.com/en/CUDA#GPUs_supported](https://www.wikiwand.com/en/CUDA#GPUs_supported)  

Compute Capability check

<img src="/posts_img/CUDA+CuDNN+TF_Setting/Compute_Capability_check.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="Compute_Capability_check">

  

Micro-architecture : Ampere  

Compute capability: 8.6  

  

<img src="/posts_img/CUDA+CuDNN+TF_Setting/GPUs_supported.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="GPUs_supported">

  

Available CUDA SDK version : 11.1-11.4  

Fixed CUDA ver. - 11.2  

  
## CUDA Installation
CUDA toolkit archive  
[https://developer.nvidia.com/cuda-toolkit-archive](https://developer.nvidia.com/cuda-toolkit-archive)
  

CUDA-11.2  
[https://developer.nvidia.com/cuda-11.2.0-download-archive](https://developer.nvidia.com/cuda-11.2.0-download-archive)  

<img src="/posts_img/CUDA+CuDNN+TF_Setting/CUDA_11.2_toolkit_download_1.jpg" width="60%" height="40%" title="px(픽셀) 크기 설정" alt="CUDA_11.2_toolkit_download_1">
<img src="/posts_img/CUDA+CuDNN+TF_Setting/CUDA_11.2_toolkit_download_2.jpg" width="60%" height="40%" title="px(픽셀) 크기 설정" alt="CUDA_11.2_toolkit_download_2">
<img src="/posts_img/CUDA+CuDNN+TF_Setting/CUDA_11.2_toolkit_install_1.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="CUDA_11.2_toolkit_install_1"> 
<img src="/posts_img/CUDA+CuDNN+TF_Setting/CUDA_11.2_toolkit_install_2.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="CUDA_11.2_toolkit_install_2"> 
<img src="/posts_img/CUDA+CuDNN+TF_Setting/CUDA_11.2_toolkit_install_3.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="CUDA_11.2_toolkit_install_3"> 
<img src="/posts_img/CUDA+CuDNN+TF_Setting/CUDA_11.2_toolkit_install_4.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="CUDA_11.2_toolkit_install_4"> 
  
## cuDNN Installation  
<img src="/posts_img/CUDA+CuDNN+TF_Setting/cuDNN_v8.1.0_install_1.jpg" width="60%" height="40%" title="px(픽셀) 크기 설정" alt="cuDNN_v8.1.0_install_1">  
  
  
install available after login  
[https://en.wikipedia.org/wiki/Quadro](https://en.wikipedia.org/wiki/Quadro)  


<img src="/posts_img/CUDA+CuDNN+TF_Setting/cuDNN_v8.1.0_install_2.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="cuDNN_v8.1.0_install_2">  
  
extract zip file  
  
<img src="/posts_img/CUDA+CuDNN+TF_Setting/cuDNN_v8.1.0_install_3.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="cuDNN_v8.1.0_install_3">  
  
<img src="/posts_img/CUDA+CuDNN+TF_Setting/cuDNN_v8.1.0_install_4.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="cuDNN_v8.1.0_install_4">  
<img src="/posts_img/CUDA+CuDNN+TF_Setting/cuDNN_v8.1.0_install_5.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="cuDNN_v8.1.0_install_5">  

*****
  
# 5. TENSORFLOW  

Tensorflow - CUDA build configuration  
[https://www.tensorflow.org/install/source_windows?hl=en#gpu](https://www.tensorflow.org/install/source_windows?hl=en#gpu)  
<img src="/posts_img/CUDA+CuDNN+TF_Setting/TF_CUDA_cuDNN.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="TF_CUDA_cuDNN"> 
  
TF-2.10.0  
CUDA 11.2  
cuDNN 8.1  
tensorflow installation  

```
(tf310) PS C:\Users\ParkLab> conda install tensorflow==2.10.0
```
but by unknown reason, When I install tensorflow with conda command, (conda install tensorflow\==2.10.0), it couldn't find GPU device via tensorflow. I changed installation option to pip.  
```  
(tf310) C:\Windows\system32>conda uninstall tensorflow 
(tf310) C:\Windows\system32>pip install tensorflow==2.10.0 
(tf310) C:\Windows\system32>pip install brotli
```  
Tensorflow GPU device connection check  
```
(tf310) C:\Windows\system32>python Python 3.10.11 | packaged by Anaconda, Inc. | (main, Apr 20 2023, 18:56:50) [MSC v.1916 64 bit (AMD64)] on win32 Type "help", "copyright", "credits" or "license" for more information. 
>>> import tensorflow as tf 
>>> tf.test.is_built_with_cuda() 
True 
>>> tf.config.list_physical_devices('GPU') [PhysicalDevice(name='/physical_device:GPU:0', device_type='GPU'), PhysicalDevice(name='/physical_device:GPU:1', device_type='GPU')]
```  

*****

# 6. PyTorch  
  
create new environment for PyTorch option.  
```
(base) C:\Users\ParkLab>conda create -n pt39 python==3.9 
(base) C:\Users\ParkLab>conda activate pt39 
(pt39) C:\Users\ParkLab>conda pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu111
```  
  
Installation details:  
torch-1.10.2+cu111  
torchvision-0.10.1+cu111  
torchaudio-0.10.1+cu111  
  
```
(pt39) C:\Users\ParkLab>python Python 3.9.16 (main, Mar 8 2023, 10:39:24) [MSC v.1916 64 bit (AMD64)] on win32 Type "help", "copyright", "credits" or "license" for more information. 
>>> import torch 
>>> torch.cuda.is_available() 
True
```  

*****