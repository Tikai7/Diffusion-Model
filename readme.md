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

- Here is an example of a generated emoji : 
