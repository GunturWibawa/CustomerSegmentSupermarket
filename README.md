# CustomerSegmentSupermarket

Customer Segmentation of Good Seed Retail Supermarket

The project assigned to me during the fifteenth sprint involves Computer Vision.

Throughout this sprint, I dived into computer vision on its key principles including artificial neural network, and convolutional neural network to train multilayer network.

# **Project Overview**

Good Seed, a prominent supermarket chain, is exploring the potential of Data Science to reinforce compliance with alcohol laws, specifically to prevent the sale of alcohol to underage individuals. I have been entrusted with the responsibility of conducting this critical evaluation, guided by the following principles:

1. The stores are equipped with specialized cameras in the checkout zones, activated whenever a purchase of alcohol is detected.
2. State-of-the-art computer vision techniques are employed to ensure an individual's age from a captured photograph.
3. The main objective involves the design, construction, and assessment of a predictive model dedicated to verify a person's age.

For this significant initiative, I engineered a model that capable to recognize a person's age through photographic analysis. I implemented the renowned ResNet50 architecture, augmented with a 'relu' activation function to neutralize negative values, and appended an additional terminal layer consisting of a single neuron. This configuration facilitates the production of a solitary output which derived through regression. The designated loss function was 'mse', and the metric applied was 'mae'. I consciously refrained from employing any form of augmentation in the limitation of training and testing sets. The model's performance reached its peak in a minimum MAE value of 3.1716.

