## Waste Classification Using CNN
#### **What is the purpose of this package?**
Waste disposal is a major challenge in environmental management, which is largely because classifying
different types of waste can be quite complicated. Traditional sorting methods usually simplify waste into
just landfill or recyclable categories, which can miss important details about specific types, like organic
materials and hazardous substances. In our project, we aim to improve waste classification by developing
a new convolutional neural network (CNN) model using the RealWaste dataset. This approach not only
improves accuracy but also helps with better resource recovery and raises public awareness about effective
waste management.  
  
We built our CNN model using the Keras library and took advantage of its powerful features for extracting
and classifying data. By comparing the performance of our custom model with the well-known VGG16
model, we hope to show how deep learning techniques can significantly improve waste classification and
contribute to more sustainable waste management practices.  
  
Accuracy: The custom model achieved a training accuracy of 63.48% and a validation accuracy of
66.39% after 25 epochs. The model showed effective learning over epochs as the accuracy continuously
increased with some minor fluctuations.  
Loss: Both training and validation loss gradually decreased, stabilizing around 1.0 at the end of
training. The validation loss (0.988) was slightly lower than the training loss (1.0395) which indicates
that the model was not overfitting. This was consistent over most of the epochs.
