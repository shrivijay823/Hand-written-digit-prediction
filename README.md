# Hand-written-digit-prediction

### Hand written digit predictor is a Neural network model which predicts the value of hand written digit.

## Neural Network (NN)
Neural networks, also known as artificial neural networks (ANNs) or simulated neural networks (SNNs), are a subset of machine learning and are at the heart of deep learning algorithms. Their name and structure are inspired by the human brain, mimicking the way that biological neurons signal to one another.Artificial neural networks (ANNs) are comprised of a node layers, containing an input layer, one or more hidden layers, and an output layer.

![neural network](https://miro.medium.com/max/875/1*zyBS2RsuRsEXINPXUGXOgg.png)

## 1. Loading and Visualizing Data 
* We first load the dataset from *dataset.mat* where each sample in the dataset is *20x20* input images of digit and the target vaiables of the sample are label from (1 to 10). (note that we have mapped "0" to label 10).
* Now we randomly select 100 data sample and passs it into displayData for visualization
![sample data visualization](https://github.com/shrivijay823/Hand-written-digit-prediction/blob/outputs/samples%20visz.png)


## 2. Loading Parameters
* Artificial neural networks (ANNs) are comprised of a node layers, containing an input layer, one or more hidden layers, and an output layer. Each node, or artificial neuron, connects to another and has an associated weight and threshold. So now we load the pre-initialized weights for the activation units from *auweights.mat*. 
* *Our model for Hand written Digit prediction uses 1 hidden layer which has 25 activation unit in it*

## 3. Prediction Implementation
* Our input nodes (layer 1), also known as the "input layer", go into another node (layer 2), which finally outputs the hypothesis function, known as the "output layer".
![eq](https://latex.codecogs.com/png.latex?%5Cbg_white%20%5CLARGE%20%5Bx_%7B0%7D%20x_%7B1%7D%20x_%7B2%7D...x_%7Bn%7D%5D%5Crightarrow%20%5Ba_%7B0%7D%20a_%7B1%7Da_%7B2%7D...a_%7Bn%7D%5D%5Crightarrow%20h_%7B%5CTheta%7D%28x%29)

  * Each data sample is a 20x20 grayscale image so the we have 400 input units in input layer
  * we have one hidden layer which 25 activation units 
  * Finally output layer contain 10 unit where each unit represents a digit from (0 to 9)
  ![eq2](https://latex.codecogs.com/png.latex?%5Cinline%20%5Cbg_white%20%5CLARGE%20a%5E%7B%28j%29%7D_%7Bi%7D%3D%20%5Ctext%7B%22activation%22%20of%20unit%20i%20in%20layer%20j%7D%20%5C%5C%20%5CTheta%5E%7B%28j%29%7D%3D%5Ctext%7Bmatrix%20of%20weights%20controlling%20function%20mapping%20from%20layer%20j%20to%20layer%20j&plus;1%7D)
 
 







