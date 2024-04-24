# Using CNN's with the Cats vs Dogs Dataset

1. **Download Dataset**:
   - Download the dataset from [Kaggle Dogs vs Cats Competition](https://www.kaggle.com/c/dogs-vs-cats) or [Microsoft Cats vs Dogs Dataset](https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765).
   - Extract the zip file and ensure the directory structure is as described in the notebook.

2. **Train-Validation Split**:
   - Refer to the section "Week 1: Using CNN's with the Cats vs Dogs Dataset" in the notebook.
   - Make sure the `cats-v-dogs` directory has been created with subdirectories `training` and `validation`, and subdirectories `cats` and `dogs` inside them.
   - Use the `split_data` function to split the dataset into training and validation data.

3. **Create Model**:
   - Refer to the "create_model" section in the notebook.
   - Implement the `create_model` function to build a CNN model using TensorFlow/Keras.
   - Ensure the model has at least 3 convolutional layers.

4. **Train Model**:
   - Refer to the "Train the model" section in the notebook.
   - Use the created model to train the data using the `fit` function.
   - Specify an appropriate number of epochs and monitor the output to see the accuracy and loss at each epoch.

5. **Visualize Training Results**:
   - Refer to the "Plot training and validation accuracy per epoch" and "Plot training and validation loss per epoch" sections in the notebook.
   - Visualize the accuracy and loss at each epoch using matplotlib.

6. **Download History File**:
   - If the model training is completed and you want to save the training history, run the cell that calls the `download_history` function.
   - The `history.pkl` file will be downloaded and you can save it along with your notebook.
  
*Notes*
You will need these packages if you will run the notebooks locally:
tensorflow==2.7.0
scikit-learn==1.0.1
pandas==1.1.5
matplotlib==3.2.2
seaborn==0.11.2

By following the above steps, you can run and train your own model to classify cat and dog images.
