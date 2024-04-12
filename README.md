<h1>Detection of the presence of St. George in an image</h1>
<h2>Summary</h2>
<ul>
  <li><p>Introduction</p></li>
  <p>In this project, the task is to detect the presence of St. George in a given image. This is achieved by training a deep learning model using a dataset consisting of images with and without St. George. This report explains the choice of model, evaluation metrics, and the results obtained. Additionally, it includes a function that takes an image as input and classifies it based on the presence or absence of St. George.</p>
  <li><p>Model which is used</p></li>
  <p>The VGG16 model was chosen for this task due to its success in image classification tasks. It is a pre-trained model that has been trained on a large dataset (ImageNet) and has proven to be a robust and accurate model for various image classification tasks. The VGG16 model is a deep convolutional neural network (CNN) that consists of 16 layers, including 13 convolutional layers and 3 fully connected layers. The model is known for its simplicity and high performance, making it an ideal choice for this task.</p>
  <li><p>Evaluation Metrics</p></li>
  <p>The evaluation metrics used for this task are accuracy, precision, recall, and F1 score.Accuracy is the ratio of the number of correct predictions to the total number of predictions. Precision is the ratio of true positive predictions to the total number of positive predictions. Recall is the ratio of true positive predictions to the total number of actual positive instances. The F1 score is the harmonic mean of precision and recall. These metrics were chosen to evaluate the performance of the model in detecting the presence of St. George in an image.</p>
  <li><p>Training Result</p></li>
  <p>The model was trained on a dataset consisting of 2680 images with St. George and 3366 images without St. George. The model achieved an accuracy of 86%, a precision of 84%, a recall of 83%, and an F1 score of 84%. These results indicate that the model is highly accurate in detecting the presence of St. George in an image.</p>
  <li><p>Conclusion</p></li>
  <p>In this project, we have developed an image classification model to detect the presence of St. George in a given image. We used the VGG16 model, which is a pre-trained convolutional neural network (CNN) architecture that has been successful in various image classification tasks. We fine-tuned the model by freezing the weights of the pre-trained layers and adding new hidden layers with 256 units and an output layer with two units at the end, one for each class (St. George and not St. George). We also added a Dropout layer to avoid overfitting.</p>
</ul>

<h2>Final Result</h2>
<ul>
  <li><b>Accuracy</b></li>

   ![WhatsApp Image 2024-04-12 at 5 31 57 PM](https://github.com/SomnathBiswas/Image_Detection_System/assets/108716703/3ee28b36-54c7-42ad-86e4-fd5e6d5e12a7)


  <li>Other Evaluations</li>

  
![WhatsApp Image 2024-04-12 at 5 13 11 PM](https://github.com/SomnathBiswas/Image_Detection_System/assets/108716703/ee904818-b6b5-43c8-b324-8ce50f1fe676)

  <li><b>Outcome</b></li>

  ![WhatsApp Image 2024-04-12 at 5 32 26 PM](https://github.com/SomnathBiswas/Image_Detection_System/assets/108716703/d0cc9a9e-2730-42fb-8065-a9eedc97613e)


</ul>

