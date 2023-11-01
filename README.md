# Classification-on-Fashion-MNIST-Images-Data-Set-using-PCA-SVM-Bayes-KNN-and-MLP
The Fashion-MNIST dataset is a collection of images consisting of 70,000 grayscale images of fashion products, each with a size of 28x28 pixels.  
The dataset is split into a training set of 60,000 images and a test set of 10,000 images.  
The images are classified into 10 different categories, including T-shirts/tops, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots.  

  
After the data was loaded and the labels were separated from the training features, pre-processing was performed on the data.  

Then, Principal Component Analysis (PCA) was performed on the training data using my own implementation. Python built-in PCA also was used and their results was compared.  

Following that, 5-fold cross validation was employed on the training data for finding the best hyperparameters for each subsequent model usage.  

Four models including support vector machines (SVM), Bayes, k-nearest neighbors (KNN), and multilayer perceptron (MLP) were trained on the selected features.  

At last, 4 evaluation metrics: accuracy, precision, recall, and f1 score along with a confusion matrix were applyed on both training and test datasets and their obtained results were compared.  

According to the predicted comparison, the MLP result was the most acceptable and credited one for this dataset, whereas others also are well-done models on their more related and consistent datasets.
