# Emotion_AI

Purpose of this project:
1. Learn to harness AI for recognizing human emotional states.
2. Grasp the fundamental concepts and reasoning behind the design of residual neural networks.
3. Create and train artificial neural network models using Google Colab, taking advantage of powerful GPU and TPU resources.
4. Construct, train, evaluate, and apply resnets for categorizing images with datasets from the real world.
5. Utilize image augmentation techniques to enhance the model's ability to generalize.
6. Assess the performance of resnet models on test data using a variety of key performance indicators.
7. Comprehend the distinctions between the Sigmoid function and the ReLU activation function.
8. Employ the Keras API along with TensorFlow 2.0 to develop complex convolutional neural networks.
9. Understand the differences between the metrics of precision and recall.
10. Execute combined predictions using models that identify key facial points and classify facial expressions.
11. Implement and use deep neural networks with TensorFlow 2.0 for making predictions. <br/>

Artificial Emotional Intelligence or Emotion AI allows computers to understand non verbal cues such as body movements and facial expressions. This project has an overarching classification problem: to classify people's emotions based on their facial expressions in their face images. We have over 20,000 facial images, with their associated facial expression labels and about 2,000 images with their primary facial notations.

As a result, we are going to train an emotional AI model which would parse through an original input image and make two predictions:
1. The emotion reflected on the person's face (anger/happiness/sadness etc.), and
2. key facial points ((x,y) coordinates of facial features such as eyes, nose, mouth, and so on). <br />

Using these two predictions, we will get the combined predictions of the people's emotions.
<br />
# Part 1 - Primary Facial Features Point Detection:
In this section, we will create a deep learning model based on CNNs and Residual Blocks to predict where the primary facial features are located.

We have a dataset with gray-scale images of 96x96 pixels consisting of the x and y coordinates of the 15 facial features. We will perform this detection using the following steps:
1. Image visualization with facial key points marked
2. Image augmentation (create an additional dataset with images flipped horizontally and vertically, images in increased brightness and darkness, and images zoomed in and zoomed out)
3. Data normalization and training data preparation
4. **Build deep residual neural network facial feature detection model**
5. Compile and train primary facial features detection deep learning model
6. Assess trained key facial features detection model performance
# Part 2 - Facial Expression Detection:
In this section, we will train a model to take images as input and classify people's emotions. We have data that contains images belonging to 5 categories:
1. 0 = Anger
2. 1 = Disgust
3. 2 = Sad
4. 3 = Happy
5. 4 = Surprise
This is a classification problem, classifying people's expressions into 5 categories.

Our input images will be of 48x48 pixels. Our classifier, a deep learning model, will feed in the images and classify the facial expressions into their corresponding emotion categories. We will perform the following steps:
1. Exploratory data analysis
2. Visualize images and plot labels for expression detection
3. Image augmentation and training data preparation
4. Build and train deep learning model for facial expression classification
5. Assess the performance of trained facial expression classifier model

Important to note: Many datasets and models were very large in size and so have not been added to the repository.

