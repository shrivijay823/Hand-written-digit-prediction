# Hand-written-digit-prediction

### Hand written digit predictor is a Neural network model which predicts the value of hand written digit.

## Artificial Neural Network (NN)
Among several ways of implementing deep learning, neural networks are by far the most popular. In short, they are a stack of simple learning algorithms (called layers) that sequentially process the input, producing an output. This embodies the idea of deep learning by design, as each layer learns a more refined understanding of the input.

![neural network](https://miro.medium.com/max/875/1*zyBS2RsuRsEXINPXUGXOgg.png)

## 1. Loading and Visualizing Data 
* We first load the dataset from *dataset.mat* where each sample in the dataset is *20x20* input images of digit and the target vaiables of the sample are label from (1 to 10). (note that we have mapped "0" to label 10).
* Now we randomly select 100 data sample and passs it into displayData for visualization
![sample data visualization](https://github.com/shrivijay823/Hand-written-digit-prediction/blob/outputs/samples%20visz.png)


## 2. Loading Parameters
* Neural networks contains hidden layers which contains activation units, each activation unit carries some weight. So now we load the pre-initialized weights for the activation units from *auweights.mat*. 
* Hand written Digit prediction model uses 1 hidden layer which has 25 activation unit in it

## 3. Prediction Implementation



