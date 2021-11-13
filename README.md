# Gesture_Recognition_Case_Study
Gesture Recognition Group Case Study

By:
1. Rangareddy Annapareddy (Group Facilitator)
2. Himanshu Srivastava

In this group project, you are going to build a 3D Conv model that will be able to predict the 5 gestures correctly. Please import the following libraries to get started.

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

Project Overview:
In this group project, you are going to build a 3D Conv model that will be able to predict the 5 gestures correctly. Please import the following libraries to get started.

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use.

Homogenous data will not be there. It will come from various source of different sizes like 360 * 360 and 120 * 160 pixels. So to utilize them we have to make them uniform in size.

Goals of this Project:
Build a model to recognise 5 hand gestures. The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

• Thumbs up:  Increase the volume
• Thumbs down: Decrease the volume
• Left swipe: 'Jump' backwards 10 seconds
• Right swipe: 'Jump' forward 10 seconds  
• Stop: Pause the movie
We need to accomplish the following in the project:

Generator: The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.
Model: Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved.
Write up: This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model.
