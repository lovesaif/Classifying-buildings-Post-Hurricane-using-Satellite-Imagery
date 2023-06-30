# Classifying-buildings-Post-Hurricane-using-Satellite-Imagery

After a hurricane, damage assessment is vital to the relief helpers and first responders so that resources and help can be planned and allocated appropriately. One way to measure the damage is to detect and quantify the number of damaged buildings, usually done by driving around the affected area and noting down manually. This process can be labor-intensive and time-consuming and not the most efficient method as well. Hence in this project, we classify buildings between damaged and not damaged buildings using the satellite imagery data.

This repository contains the code for a project that uses computer vision and machine learning to classify hurricane-damaged buildings from satellite images.

Overview
The goal of this project was to create a model that could tell if a building was damaged or not. There are two classes "no damage" and "damage".This was a challenging task because the images had different qualities and water could make it harder to see the damage.

Dataset Collected 
The dataset is collected from "Geo-satellite sensor" and "Geo Bigdata".
Code for downloading dataset is inside the notebook.

Approach
Our approach included the following steps:

Preprocessing the data to handle variations in image quality, resolution, and the presence of water in the images.
Conducting extensive training using a labeled dataset and employing popular pre-trained models such as AlexNet, VGG16, and Xception through transfer learning and fine-tuning.
Applying innovative techniques to enhance the training process, such as data augmentation and image sharpening.
Results
In the end, the Xception model outperformed the others, achieving an accuracy of 89%. This robust and accurate classification model can be valuable for efficient post-hurricane damage assessment and providing aid to relief efforts.

Usage
The code in this repository can be used to train and deploy a hurricane-damaged building classification model. The following instructions will help you get started:

Clone the repository.
Install the dependencies.
Download the data.
Train the model.
Deploy the model.
Documentation
The documentation for this project can be found in the docs directory.

Contact
If you have any questions or feedback, please contact me at [nazimsaifi9@gmail.com].

I hope this is helpful!
