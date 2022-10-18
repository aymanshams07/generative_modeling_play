## Generative modeling (GANS, GAN+VAE, Music Transformer), and Ai Art and Creativity


## Project 1 : UnPaired image-to-image translation using cycle consistent GANs for Sim2Real task 

- Project aims to reduce reality gap by using Generative Adversarial Networks to generate realistic images from simullation images. 
-  The UNIT model was able to learn a generative model that could generate quite realistic images from synthetic images.
- UNIT attempts to learn the same mapping G : X -> Y as CycleGAN, but it uses a slightly different approach, by enforcing the idea of a shared latent space between pairs of images and using Variational Auto Encoders (VAE) in addition to a GAN network. Thus, UNIT tries to learn that shared latent space and tries to minimize the cycle consistency loss, the VAE losses as well as the adversarial losses.
- https://github.com/duckietown/course-extra/blob/daffy/book/course-extra/70_montreal_2020/10_project_reports_montreal_2020/04-sim2real/01_project-report-sim2real.md


## Project 1 part 2: Style transfer for Duckietown

- Style transfer is a system which uses neural represenations to separate and recombine content and style of arbitrary images. This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image.
- VGG-19 CNN architecture is used to extract both the content and style features from the content and style images respectively.
- check project report

## Project 3 : Face Recognition

- Project report 
- https://docs.google.com/document/d/11p0kalhKnpEl-ZTEpxwSHA3AIvaukwr7S6v5ZMj9Mbs/edit?usp=sharing
- worked on a dataset of facial images of dimension 650 X 506 X 3
- performed PCA to reduce dimentionality of the images
- The eigenface method was used to  recognise an input image. Euclidean distance between this input image eigenface and the previously stored eigenface are calculated, the eigenface with the smallest Euclidean distance is the one the  person resembles the most. 
- More details of the code will be produced when asked

## Project 4 : Using music transformer to generate music and then make generative model GAN react to the music (Audio-reactive Latent Interpolations with StyleGAN)
Example of work
- https://drive.google.com/file/d/1yKflC5aIhLaty2Q5TfxqJqWd9MqIb1bl/view?usp=sharing
- https://drive.google.com/file/d/1Z-12ax042iECnG2N8_pUzwhr1fY63xi2/view?usp=sharing
