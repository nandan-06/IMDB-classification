### IMDB reviews binary classification

- IMDB data has 2 classes, class 0 represents negative ratings and class 1 represents positive ratings.
- Loaded the IMDB data from keras.
- Splitted data into the training and test data.
- As the data were in numbers, converted them to word for better understanding.
- Vectorized the data.
- Defined the dense layers in the model.
- 2 layers each with 16 unit output and activation of `relu`.
- 1 layer with 1 unit output and activation of `sigmoid`.
- Splitted the training data into train and validation dataset.
- Trained the model with 20 epochs.
