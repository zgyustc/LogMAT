# LogMAT: Completing any borehole images
##### Zhiguo Yang, Xinming Wu*, Xu Pang, Hanlin Sheng, Xu Si, Guangyu Wang, Liu Yang, Chaofeng Wang
****
🔥🔥🔥 We propose a deep-learning approach with a hybrid CNN and Transformer architecture to fill in the gaps in borehole images, addressing the challenges of missing training labels and filling large-scale gaps. 🔥🔥🔥
****
# Usage 🖌🖌🖌
It is highly recommanded to adopt conda to manage the environment to avoid some compilation errors.
1. Clone the repository.
```
git clone https://github.com/zgyustc/LogMAT
```
2. Install the dependencies.
* python 3.7.16
* torch 1.7.1
* cuda 10.2

# Quick Test 🚀🚀🚀
We provide models trained on Places365-Standard, seismic image and borehole image at 512x512 resolution. 
Download models from [goole_drive](https://drive.google.com/drive/folders/1ddOrHftMcMm9y-t1E_ITaxtdy2CdpFgJ) and put them into the 'pretrained' directory. 
Download some test data from [goole_drive](https://drive.google.com/drive/folders/1e236iDPCyNxTARJW3ii59s51WQ1y6KwJ) and put them into the 'test' directory. 

# Visualization 🌎🌎🌎
We present a transformer-based model (MAT) for large hole inpainting with high fidelity and diversity.


# Train 🔍🔍🔍
If you want to train a model on you dateset, run a bash script with


# Citation 🤝🤝🤝

# License and Acknowledgement
The code and models in this repo are for research purposes only. Our code is bulit upon [StyleGAN2-ADA](https://github.com/NVlabs/stylegan2-ada-pytorch) and [MAT](https://github.com/fenglinglwb/MAT).
