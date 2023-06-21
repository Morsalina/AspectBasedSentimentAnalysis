# AspectBasedSentimentAnalysis
The increase in online marketing platform usage has given an opportunity to express one’s thoughts and ideas about products, and organizations to everyone. People expresses
their reviews on many sector which caused rise in big data based researches. These reviews can be used as a medium for determining one’s sentimental behavior. Analysis of sentiment can
be done into 3 parts: analyzing sentiment of the whole document, analyzing sentiment of text, and analyzing sentiment of the aspect
level [Hu and Liu, 2004]. In our pattern recognition project, we are using a deep learning model “LSTM”(Long Short-Term Memory) and BiLSTM to analyze the sentiment of an aspect of
a sentence. We have incorporated attention with these models.

## Dataset
For this task, we have used a publicly available dataset [Rahman and Kumar Dey, 2018] to train our model. This dataset contains 2 different types of dataset. We have used
only one of them, restaurant dataset for our task.

## Experiment Results
For the first approach, <br />
#of epochs = 50, <br />
Loss function = sparse categorical crossentropy, <br />
Optimizer = Adam,<br />
Learning rate = ReduceLROnPlateau, which reduces the learning rate when loss does not decrease. <br />
Validation accuracy = 66.58% <br />
Test accuracy = 66.32%<br />

For the second approach, <br />
#of epochs = 20, <br />
Loss function = sparse categorical crossentropy, <br />
Optimizer = Adam, <br />
Learning rate = ReduceLROnPlateau, which reduces the learning rate when loss does not decrease. <br />
Validation accuracy = 70.44% <br />
Test accuracy = 69.92%
