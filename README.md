# Gender Classification Using VGG16

This project is a Gender Classification Model built Using VGG16 model , uses a convolutional neural network (CNN) layers to accurately classify images as male or female. Utilizing the VGG16 architecture, known for its strong feature extraction capabilities, this project is designed to achieve high levels of accuracy in distinguishing between genders based on visual data.

The dataset consists of 100,000 images, evenly split between male and female subjects, with 50,000 images used for training and 17,000 for testing. The model incorporates essential layers such as convolutional layers for feature extraction, batch normalization for stability, dropout layers to reduce overfitting, and dense layers for final classifications.

During the training process, data augmentation techniques are employed to enhance the diversity of the training dataset, including image transformations like rotation and flipping. This approach improves the model's robustness and ability to generalize to unseen data.

Upon evaluation, the model achieves an impressive overall accuracy of 95%. Specific metrics indicate a precision of 0.96 for males and 0.93 for females, along with recall scores of 0.93 and 0.96, respectively. The F1-scores calculated for both classes are 0.94 and 0.95, showcasing a strong balance between precision and recall.

# Results
The model demonstrates an accuracy of 95%, with precision values of 0.96 for class 0 (Male) and 0.93 for class 1 (Female). The recall values stand at 0.93 for males and 0.96 for females, leading to F1-scores of 0.94 and 0.95, respectively. These metrics indicate that the model performs efficiently in distinguishing between male and female images.

![comfusion matrix_metrics](https://github.com/user-attachments/assets/d1ba6fbd-c681-41ae-9e03-51141e83e029)


The google drive consists of all contents required. Link to Gdrive :-
https://drive.google.com/drive/folders/1_VMMZ2HkSQkRdlWJlS7hj7k1njaN6txC?usp=sharing
