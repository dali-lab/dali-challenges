# Data Challenge 📈

Not a front-end or back-end fan? Not feeling like recreating social media? Feeling a little adventurous and creative? This is the challenge for you.

### Overview

As you probably know, data science is an incredibly expansive and diverse field and a data scientist can be many different things. Here at DALI, the data team is focused on two main tracks: data visualization and machine learning. In your application, you have indicated which track you are applying for. Accordingly, we have created two main challenges for you. Please complete the challenge associated with the track you want to join. If you are applying for both tracks, please submit both challenges.
If you have prior experience in computer vision or natural language processing and want to show off your skills, then you can additionally submit one or both of the optional challenges. Please note that these challenges are completely optional and not completing them will not negatively impact your application in any way!
Further, note that we value quality over quantity! We would much rather see you submit a single clean and well-crafted model than three models that could need some more work.

### Main Challenges

For the main challenges, we have compiled two datasets for you. The first dataset is retail sales data at a fictional superstore located in the `Sample - Superstore` CSV file. The second dataset is Dartmouth course data located in the `Dartmouth - Courses` CSV file. You can find both files in the `data` folder. Feel free to use either one of them! You do not have to use both.

## 1. Data Visualization

Describe the dataset given with three or more data visualizations. These can be maps, histograms, line graphs, 
combinations of those, or anything else. It can be a time-series or even an animated or interactive plot.

Please create all graphs using a Javascript library. Here are two that we would recommend:
    - [d3.js](https://d3js.org/) is a phenomenal Javascript library that makes web visualizations incredibly easy and powerful
    - [three.js](https://threejs.org/) is another powerful Javascript visualization library

Think, if you could only show someone these graphs to describe most of the data, what graphs would you choose?

Design matters, making this beautiful matters.

The sky is the limit!

## 2. Machine Learning

This part is more free-form and allows you to showcase your machine learning skills!

Model this data! Predict some outcome, make some claims, show your work, analyze it statistically, and tell us your thinking all the way through. You can use any type of supervised or unsupervised machine learning or deep learning model you want. Whatever interests you, go for it!

Be creative, think big, and report your findings in a clean, clear way!

Here are some key concepts to watch out for:
    - Data imputation and exploration
    - Preventing data and information leakage during training
    - Hyperparameter tuning and validation

Looking for where to start? Here are our favorite frameworks and ML tools:
    - [Scikit-Learn](https://scikit-learn.org/stable/), a great place for beginners and advanced alike. An amazing, comprehensive framework that is both easy to start with, and extremely deep.
    - [Tensorflow](https://www.tensorflow.org/) from Google, is a popular Deep Learning framework 
    - [PyTorch](https://pytorch.org/docs/) from Meta, another popular Deep Learning framework

### Optional Challenges

These optional challenges focus on computer vision and natural language processing. Please note that these problems are by no means trivial and we do not expect you to "solve" them. We are much more interested in the way you approach difficult real-world problems and the thought process behind your approach. Be sure to document all your work! If you do not have the time or resources to implement your ideas, you can just submit a detailed plan describing your ideas!

## 1. Computer Vision - Barnacle Counting

This task is closely related to a project the data team has been working on in 22W and 23S. In the `data` folder, you will find a `barnacle` subfolder containing several images of barnacles. Train a model that can predict the number of barnacles in an unseen image. Describe the results of your model.

Here are some approaches we have pursued:
    - Finetuning [ResNet](https://huggingface.co/docs/transformers/model_doc/resnet)
    - Working off Meta's [Segment Anything Model](https://segment-anything.com)

## 2. Natural Language Processing - Sentiment Analysis

For this task, we are giving you a number of positive and negative employee reviews for both Amazing and Google. You can find the corresponding TXT files in the `Employee Reviews` subfolder in the `data` folder. Finetune a [BERT](https://huggingface.co/docs/transformers/model_doc/bert) model to classify the sentiment of employee reviews of Google and Amazon (as positive/negative). Describe how you performed parameter tuning and why you did it in this way. Describe the results of your fine-tuned model.

A big part of machine learning is understanding how your model is arriving at its predictions. Look into an interpretability framework (e.g. SHAP) to apply to your finetuned BERT model. Then, use the output of this framework to describe a few testing examples, and for each, describe (1) what class your finetuned model predicted the example to be in (2) what textual clues led your finetuned model to predict the example as that class.
