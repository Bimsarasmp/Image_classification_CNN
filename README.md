Dataset Link: https://www.kaggle.com/datasets/alxmamaev/flowers-recognition

There are 4242 images on this dataset and there are five types of flowers that are predicted and trained on

Daisy
Dandelion
Rose
Sunflower
Tulip
For each class there are about 800 photos. Photos are with the resolution, about 320x240 pixels.
Two Convolutional Neural Network (CNN) models were developed for image classification using the "Flowers Recognition" dataset. 
Here's a clear comparison between the two models:

**Model 1 - 10 layers:**
- **Architecture:** This model consists of 10 layers, including 3 convolutional layers, 3 max-pooling layers, 2 dense layers, 1 dropout layer, and the output layer.
- **Performance:** Achieved an overall accuracy of 74% on the test dataset.
- **Precision, Recall, F1-score:** The precision, recall, and F1-score for each class vary between 0.61 to 0.80, indicating decent performance across different classes.
- **Model Complexity:** Total trainable parameters: 17,526,597.

**Model 2 - 27 layers:**
- **Architecture:** This model comprises 27 layers, including 6 convolutional blocks, each with convolutional, batch normalization, and max-pooling layers, followed by 4 dense blocks with dropout layers, and the output layer.
- **Performance:** Achieved an overall accuracy of 67% on the test dataset.
- **Precision, Recall, F1-score:** The precision, recall, and F1-score for each class vary between 0.33 to 0.79, indicating varying performance across different classes.
- **Model Complexity:** Total trainable parameters: 3,586,533.

**Comparison:**
- **Accuracy:** Model 1 outperforms Model 2 with a higher accuracy of 74% compared to 67%.
- **Complexity:** Model 2 has significantly fewer trainable parameters compared to Model 1, indicating a simpler architecture.
- **Precision and Recall:** Model 1 generally exhibits higher precision and recall across different classes compared to Model 2.

**Conclusion:**
- Model 1 demonstrates better overall performance in terms of accuracy and precision-recall trade-off.
- Model 2, despite its simpler architecture, struggles to capture the complexities of the dataset, resulting in lower accuracy and varied performance across classes.
- Depending on the specific requirements and constraints, either model may be chosen for deployment or further optimization.
