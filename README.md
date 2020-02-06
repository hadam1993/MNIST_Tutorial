# MNIST_Tutorial

This tutorial is written for those being introduced to Neural Networks using pytorch.
An emphasis for this tutorial is based on how to use your own data to train models. The way the images are stored in your local directories and called into python using pytorch's data loader can be reused for any of your projects.

To use this tutorial, please download the data from http://yann.lecun.com/exdb/mnist/

The images from these files need to be placed in the following directory structure, with their correct labels. The File Save_Mnist_images_and_labels.ipynb will help you to save the images into these directories on your local system.

    Train
        |_0
        |_1
        |_2
        |_3
        |_4
        |_5
        |_6
        |_7
        |_8
        |_9


    Test
        |_0
        |_1
        |_2
        |_3
        |_4
        |_5
        |_6
        |_7
        |_8
        |_9

After saving the images in their correct directories you can use the Recoginizing_Handwritten_Digits_pytorch.ipynb notebook to help you learn how to create a Feed Forward Neural Network to recoginize the handwritten digits.
