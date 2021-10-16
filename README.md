# CAPTCHAs_solver_CRNN

![intro](https://i.imgur.com/bpsF4fO.jpg)

A deep learning model to break CAPTCHA codes perfectly using CRNN model (Convolutional Recurrent Neural Network).

## Description

CAPTCHAs stands for the Completely Automated Public Turing test to tell Computers and Humans Apart. CAPTCHAs are tools you can use to differentiate between real users and automated users, such as bots. CAPTCHAs provide challenges that are difficult for computers to perform but relatively easy for humans.

However, these wormy and curvy text images are even difficult for humans to figure out sometimes.

Therefore, it would be great to have an super accurate machine learning model to help you reveal these correct texts everytime without fail.

## Architecture

![architecture](https://i.imgur.com/npfKiCa.jpg)

This project will use state of the art CRNN model which is a combination of CNN, RNN and CTC loss for image-based sequence recognition tasks, specially OCR (Optical Character Recognition) task which is perfect for CAPTCHAs.

## Dataset 

The dataset is generated by the most popular Wordpress CAPTCHAs plugin with nearly 8 millions downloads (https://wordpress.org/plugins/really-simple-captcha/)

![dataset](https://i.imgur.com/zYz5Qtl.gif)

It generates 4-letter CAPTCHAs using a random mix of four different fonts.

## Result

* Here is our result:

![result](https://i.imgur.com/CLAkqda.png)

* With the perfect metrics:
    * Character Error Rate: 0.0
    * Word Error Rate:      0.0
    * Sequence Error Rate:  0.0