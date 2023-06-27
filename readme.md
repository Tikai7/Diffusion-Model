
![ddpm_04](https://github.com/Tikai7/Diffusion-Model/assets/68500496/f145a11c-1399-48b1-9585-e7fb0592fc53)
![ddpm_4](https://github.com/Tikai7/Diffusion-Model/assets/68500496/bdce727a-f6b3-4df9-b636-e0027fc8c3bb)
![ddpm_8](https://github.com/Tikai7/Diffusion-Model/assets/68500496/741f5499-6ac7-49e9-b02f-c58be32e26af)
![ddpm_013](https://github.com/Tikai7/Diffusion-Model/assets/68500496/22db5bd0-d311-4519-bfe4-7a368acbcf5e)
![ddpm_014](https://github.com/Tikai7/Diffusion-Model/assets/68500496/ff2fee1c-b532-4ace-bb4b-4cf4463fb163)

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
![generated_emojis](https://github.com/Tikai7/Diffusion-Model/assets/68500496/534dbbea-5305-4503-ae8a-9380515db9ee)
