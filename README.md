# CNN-based-Xray-Classifier
Convolutional Neural Networks for classifying chest Xrays as a pneumonia case or a normal case. Such models can provide a first pass in rapid diagnosis of respiratory infections, speeding up the triage and treatment processes at hospitals. This is particularly so during the pandemic period, as hospitals face high volumes of patients with potential respiratory infections, often with limited manpower and resources. Model implementation detailed in "model.ipynb"

Dataset: https://www.kaggle.com/datasets/pcbreviglieri/pneumonia-xray-images


### Network Architecture


5 Convolution layers and 3 fully connected (feed-forward) neural network layers were used in this model. Max pooling with kernel size of (2,2) was implemented between convolution layers. ReLu activation functions were used in all layers and neurons, with the exception of the output (final) layer, where a sigmoid function was used due to the binary classification task at hand. 


![image](https://github.com/BrandonTayKaiheng/CNN-based-Xray-Classifier/assets/115394445/2f660c4f-7f7e-4370-9ea5-628342c0055e)



### Example of Chest X Ray Classification results 


![image](https://github.com/BrandonTayKaiheng/CNN-based-Xray-Classifier/assets/115394445/2f14ec52-bca2-43d0-9331-0dd549b70851)



### Model Performance


Confusion Matrix


![image](https://github.com/BrandonTayKaiheng/CNN-based-Xray-Classifier/assets/115394445/f2d9ee21-ca81-426b-8de9-914609625fc7)


Loss-Epoch Plots


![image](https://github.com/BrandonTayKaiheng/CNN-based-Xray-Classifier/assets/115394445/e36d89ac-0d47-463c-b3bb-44ed825ff3b1)
