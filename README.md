# GANde

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

Process of gathering data and training GAN to generate faces of the American singer Ariana Grande

![Example output 2](GANde_output_2_small.gif)

Steps

1. Use OpenCV `face_recognition` to box face of Ariana Grande from full sized pictures
2. Crop face into training set
3. Set up GAN architecture, train, and save process

## Box face from full size or zoomed out images

![OpenCV Face boxing](/GANde_facecrop_illustration/fullsized_box.jpeg)

## Save face only to training set

<img src="/GANde_facecrop_illustration/facecrop_training_set.jpeg" alt="Facecrop training set" width="250">

## Example GAN outputs

![Example output 3](GANde_output_3_small.gif)

![Example output 4](GANde_output_4.gif)

## Main tools

* Google Colab - free GPU!!!
* OpenCV
* Tensorflow

## Resources

* Download pretrained model and weights (for face boxing portion) from OpenCV source GitHub
  * https://github.com/opencv/opencv/tree/master/samples/dnn/face_detector
  * https://github.com/opencv/opencv/blob/master/samples/dnn/face_detector/weights.meta4
* For the GAN portion - followed amazing tutorial by Yumi Kondo
  * https://fairyonice.github.io/My-first-GAN-using-CelebA-data.html
