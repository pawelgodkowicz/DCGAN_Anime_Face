# Anime Faces- DCGAN
This is the project ending my six-month bootcamp Sages [Kodołamacz Data Science](https://www.kodolamacz.pl/bootcamp-datascience/) organized by Sage company.

The choice of topic was guided by enthusiasm for anime and interest from deep learning.The goal of the project is to generate anime face images from noise by using Deep Convolutional Generative Adversarial Network.

# Prerequisites
- python 3.7
- tensorflow 2.1
- tensorflow-gpu 2.1
- matplotlib
- numpy
- pandas
- tqdm
- imageio
- glob
# Dataset
Dataset come from [Anime Faces - Kaggle](https://www.kaggle.com/soumikrakshit/anime-faces) and contains 21551 anime faces scraped from [Getchu.com](http://www.getchu.com/)
### Example of dataset 
![real_image.png](https://github.com/pawelgodkowicz/DCGAN_Anime_Face/blob/master/outputs_results/data_faces.png?raw=true)

# Results

## Generated Images
![generated_image.png](https://github.com/pawelgodkowicz/DCGAN_Anime_Face/blob/master/outputs_results/gener_faces.png?raw=true)

## Face sample in the training process
![process](https://github.com/pawelgodkowicz/DCGAN_Anime_Face/blob/master/outputs_results/process_faces.png?raw=true)

## Charts
<img src="https://github.com/pawelgodkowicz/DCGAN_Anime_Face/blob/master/outputs_results/gan_disc_loss.png?raw=true" width="826" height="395">
<img src="https://github.com/pawelgodkowicz/DCGAN_Anime_Face/blob/master/outputs_results/gan_disc_500.png?raw=true" width="826" height="395">
<img src="https://github.com/pawelgodkowicz/DCGAN_Anime_Face/blob/master/outputs_results/disc_f_r_loss.png?raw=true" width="826" height="395">

## Training process as a GIF: (Images generated per every 50 epoch)
![gif](https://github.com/pawelgodkowicz/DCGAN_Anime_Face/blob/master/outputs_results/png_to_gif.gif?raw=true)
