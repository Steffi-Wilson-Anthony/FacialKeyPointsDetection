### Import Libraries
- Using tensorflow and keras libraries.
### Import Dataset
- This [Dataset](https://www.kaggle.com/c/facial-keypoints-detection/data) has separate files for testing and training data.
- Although here the data from both the files have been merged.
### Data Preprocessing
- There are no null values.
### Image Augmentation
- The images are flipped vertically and also brightened.
### Normalization
- The augmented data is normalized.
### Splitting Dataset
- The testing data is 20% of the Dataset.
### Model
- Residual Neural Network with adam optimizer.
- The model is trained for `100 epochs` with a `learning rate of 0.001`.
### Model evaluation
- RMSE Value = 1.4426514744026255
- Accuracy = 0.8777258396148682
