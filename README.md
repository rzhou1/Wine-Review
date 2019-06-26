### Wine Review: Multi-Classification of Wine Varieties by Deep Learning
Here we introduce a neural network model for multi-classification of wine varieties from Wine Reviews datasets. The model consists of a bidirectional LSTM encoder for textual representative embeddings (here the wine review) and a prediction network for classification. Using only the learned embeddings as input, the model results in accuracy as high as 77% for 10-classes classification and well-balanced precision and recall. By concatenating both the learned embeddings and external features as input, the model accuracy has been improved to 82%.

##Introduction

It is of great satisfaction for wine lover if he/she could identify its variety (and even winery and manufacturing year) by having a simple taste. Such practice could be possible for those who taste wines frequently from a wide range of varieties (as well as from a wide range of wineries) like professional wine tasters. 

##Data preprocess
![Description_length_distribution](https://user-images.githubusercontent.com/34787111/60202040-a4918b80-97fe-11e9-8b3e-e5e1e81422c1.png)

Given that the goal is to predict wine variety from the review (column description in the dataset), converting textual description to ML-learnable embedding is the primary task for data preprocessing. 

![Price_dist](https://user-images.githubusercontent.com/34787111/60202059-ac513000-97fe-11e9-98ae-9b0e400f9a0d.png)

##Model
![NN_architecture](https://user-images.githubusercontent.com/34787111/60202610-c93a3300-97ff-11e9-80f1-a19dbaeec831.png)



![variety_nn_cm3](https://user-images.githubusercontent.com/34787111/60202794-3f3e9a00-9800-11e9-8e6a-a44219b133ec.png)

##Conclusion





