LogMAT
====
LogMAT--Completing any borehole images

# Usage
It is highly recommanded to adopt Conda/MiniConda to manage the environment to avoid some compilation errors.
Clone the repository.

Install the dependencies.

# Quick Test
We provide models trained on Places365-Standard, seismic image and borehole image at 512x512 resolution. Download models from One Drive and put them into the 'pretrained' directory. 

where the mask path is optional. If not assigned, random 512x512 masks will be generated. Note that 0 and 1 values in a mask refer to masked and remained pixels.

# Train
If you want to train a model on you dateset, run a bash script with

# Visualization
We present a transformer-based model (MAT) for large hole inpainting with high fidelity and diversity.

# Citation

# License and Acknowledgement
The code and models in this repo are for research purposes only. Our code is bulit upon [StyleGAN2-ADA](https://github.com/NVlabs/stylegan2-ada-pytorch) and [MAT](https://github.com/fenglinglwb/MAT).
