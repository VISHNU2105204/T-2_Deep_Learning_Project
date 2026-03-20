# Task - 2
# Deep-Learning-Project
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: BADIMELA VISHNU VARDHAN

*INTERN ID*: CTIS1342

*DOMAIN*: DATA SCIENCE

*DURATION*: 12 WEEKS

*MENTOR*: NEELA SANTHOSH

## The primary goal of this project is to develop a Convolutional Neural Network (CNN) capable of accurately identifying different types of fruits and vegetables from digital images. 
## By training on a diverse dataset comprising categories like apples, bananas, cabbage, and corn—the model learns to distinguish subtle features such as texture, color, and shape to make real-time predictions.
## The project is built using the TensorFlow and Keras frameworks. You utilized a Sequential API to stack layers, creating a pipeline that transforms raw pixel data into categorical probabilities.
## Images are resized to a uniform dimension of 180x180 pixels to ensure consistent input for the neural network. You also implemented a Rescaling layer to normalize pixel values to a range of [0, 1], which significantly improves training stability and convergence speed.
## The model employs multiple Conv2D layers with ReLU activation functions. These layers act as filters that detect "edges" in the early stages and "complex shapes" in the deeper stages. 
## Each convolutional layer is followed by a MaxPooling2D layer, which reduces the spatial dimensions of the data, helping the model focus on the most important features while reducing computational load.
## After the convolutional base, the data is "flattened" into a 1D vector and passed through Dense (fully connected) layers. The final output layer uses a Softmax activation function, which provides a probability distribution across all possible fruit/vegetable classes.
## The model was compiled using the Adam optimizer, an industry standard for its adaptive learning rate capabilities. For the loss function, you used Sparse Categorical Crossentropy, which is ideal for multi-class classification where labels are provided as integers. The training process involved iterating through training, testing, and validation datasets to ensure the model generalizes well to unseen data.
## This implementation includes a practical inference script. It processes an image (like the corn.jpg you uploaded), converts it into a batch-compatible array, and passes it through the model.
## Predictive Power: In my recent test, the model successfully identified sweetcorn with an accuracy of 78.90%.
## Softmax Output: The model doesn't just "guess"; it calculates a confidence score for every category, allowing you to see exactly how certain the AI is about its prediction.

# OUTPUT:
