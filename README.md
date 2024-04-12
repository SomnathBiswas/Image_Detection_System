<h1>Detection of the presence of St. George in an image</h1>
<h2>Summary</h2>
<ul>
  <li><p>Introduction</p></li>
  <p>In this project, the task is to detect the presence of St. George in a given image. This is achieved by training a deep learning model using a dataset consisting of images with and without St. George. This report explains the choice of model, evaluation metrics, and the results obtained. Additionally, it includes a function that takes an image as input and classifies it based on the presence or absence of St. George.</p>
  <li><p>Model which is used</p></li>
  <p>The VGG16 model was chosen for this task due to its success in image classification tasks. It is a pre-trained model that has been trained on a large dataset (ImageNet) and has proven to be a robust and accurate model for various image classification tasks. The VGG16 model is a deep convolutional neural network (CNN) that consists of 16 layers, including 13 convolutional layers and 3 fully connected layers. The model is known for its simplicity and high performance, making it an ideal choice for this task.</p>
  <li><p>Evaluation Metrics</p></li>
  <p>The evaluation metrics used for this task is find the accuracy. So Accuracy is the ratio of the number of correct predictions to the total number of predictions. Precision is the ratio of true positive predictions to the total number of positive predictions. Recall is the ratio of true positive predictions to the total number of actual positive instances. The F1 score is the harmonic mean of precision and recall. These metrics were chosen to evaluate the performance of the model in detecting the presence of St. George in an image.</p>
  <li><p>Training Result</p></li>
  <p>The model was trained on a dataset consisting of 2680 images with St. George and 3366 images without St. George. The model achieved an accuracy of 95%. These results indicate that the model is highly accurate in detecting the presence of St. George in an image.</p>
  <li><p>Conclusion</p></li>
  <p>In this project, we have developed an image classification model to detect the presence of St. George in a given image. We used the VGG16 model, which is a pre-trained convolutional neural network (CNN) architecture that has been successful in various image classification tasks. We fine-tuned the model by freezing the weights of the pre-trained layers and adding new hidden layers with 256 units and an output layer with two units at the end, one for each class (St. George and not St. George). We also added a Dropout layer to avoid overfitting.</p>
</ul>

<h3>Final Result</h3>


