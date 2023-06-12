
![Uploading ddpm-3.gif…]()
![Uploading ddpm_4.gif…]()

# ***Diffusion Model***
 - This is an simple implementation of a Diffusion model (Stable diffusion)
 in Tensorflow & Keras.
 - This code is used in Kaggle

# ***Dataset***
 - I'm using emoji images for each company such as Apple, Facebook, Twitter etc.
 - I only used the 400 first images (emojis of person/faces etc.. no flags of symbols)
 - Link to download : https://www.kaggle.com/datasets/subinium/emojiimage-dataset

# ***Model***
 - The model is built on a UNET architecture
 - We first generate a random image noisy at a certain time step, along with the accompanying noise.
 - We then feed the noisy image to the Unet model to try to denoise it, and calculate the error
 with the accompanying noise.

# ***Result***
- Here is the result after 300 epochs : 
![plot](https://github.com/Tikai7/Diffusion-Model/assets/68500496/29c59161-30a5-49bb-bb9e-258560d44d58)
- Here is an example of a generated emoji : 
![Uploading generated_emojis.JPG…]()
