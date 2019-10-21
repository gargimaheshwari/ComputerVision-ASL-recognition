# Deep Learning for ASL recognition

American Sign Language (ASL) is the primary language used by many deaf individuals in North America, and it is also used by hard-of-hearing and hearing individuals. The language is as rich as spoken languages and employs signs made with the hand, along with facial gestures and bodily postures.

A lot of recent progress has been made towards developing computer vision systems that translate sign language to spoken language. This technology often relies on complex neural network architectures that can detect subtle patterns in streaming video. However, as a first step, towards understanding how to build a translation system, we can reduce the size of the problem by translating individual letters, instead of sentences.

In this notebook I use Convolutional Neural Networks (CNN) to analyze and recognize Americal Sign Language letter symbols.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Asl_alphabet_gallaudet.png/480px-Asl_alphabet_gallaudet.png)

I begin by loading the data, displaying the images and preprocessing them. I then form a deep learning model with over 1 million parameters and test it on two different sets of data.

![](https://i.imgur.com/6Crxeo5.png)

Finally, I use the model to plot confusion matrices for both sets of testing data, which show a wealth of information about the workings of the deep learning model.

The data is taken from kaggle.com. The data files can be found [here](https://www.kaggle.com/grassknoted/asl-alphabet) and [here](https://www.kaggle.com/danrasband/asl-alphabet-test).
