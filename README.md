# Medical-Image-Classification

This repository contains the notebook with the Code from my bachelor thesis

## Idea
The idea and aim of this thesis was to apply semantic segmentation (classification of each pixel) to histologic images. More precise, I tried to detect pixels showing a special chewing muscle within a cross-section of a fetus' head with the cleft-lip syndrom. 

## Challenge
Main challenge of this idea was the dataset, which only consisted of 16 images for both training and validation. Also the distribution of pixels showing the specific muscle and pixels not showing it is hugely imbalanced, giving the model the tendency to classify the whole images as non-muslc and thereby reaching a disproportionally good performance.

## Outcome
Considering the amount of training images and the disbalance of classes, the outcome was better than expected: The model at least detected some parts of the muscle, while also of course classifying other muscles outside the chewing muscle as chewing muscle.
