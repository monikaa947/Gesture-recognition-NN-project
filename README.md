# Gesture Recognition - CNN and RNN model experiments
> Developing a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To develop the model I'll experiment multiple iterations on two diffenert architectures
    1) standard CNN + RNN architecture: in which we pass the images of a video through a CNN which extracts a feature vector for each image, and then pass the sequence of these feature vectors through an RNN. 
    2) a 3D convolutional network : 3D convolutions are a natural extension to the 2D convolutions you are already familiar with. Just like in 2D conv, you move the filter in two directions (x and y), in 3D conv, you move the filter in three directions (x, y and z).


 
- The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

    -   Thumbs up:  Increase the volume
    -   Thumbs down: Decrease the volume
    -   Left swipe: 'Jump' backwards 10 seconds
    -   Right swipe: 'Jump' forward 10 seconds  
    -   Stop: Pause the movie

- What is the dataset that is being used?
    
    The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Refer following file for different analysis over models


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow  
- Augmentor 
- Matplotlib
- Sequntial
- Resnet50
- Optimizers
- LSTM
- GRU

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@monikaa947]- feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
