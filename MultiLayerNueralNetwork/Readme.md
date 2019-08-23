This project is an attempt to make a nueral network with 1 hidden layer from scatch using numpy and some other libraries without using explicitly deep learning framework. 

For sanity check, with a dummy generated dataset with two labels the results are as follows: 

 

<p float="left">
 <img title="title-1" src="https://user-images.githubusercontent.com/26017262/63592934-ca2ddd80-c580-11e9-9f44-69c392ff976f.png"  width="200" />                                                                                            <img src="https://user-images.githubusercontent.com/26017262/63593129-488a7f80-c581-11e9-9f82-a72aee501093.png" title="title-2" width="200" /> 
  <img src="https://user-images.githubusercontent.com/26017262/63596992-73c59c80-c58a-11e9-819c-77d36528d077.png" title="title-2" width="200" /> 
</p>
train to test split 134:66,Hidden neurons:100
Accuracy on test set: 100% , F1 score:1, recall: 1, precision: 1

Using the iris dataset, the results are as follows: 

<p float="left">
 <img title="title-1" src="https://user-images.githubusercontent.com/26017262/63597810-44b02a80-c58c-11e9-9448-f0e75b1314c5.png"  width="200" />                                                 <img src="https://user-images.githubusercontent.com/26017262/63597834-52fe4680-c58c-11e9-80ac-0c1c7f4964ea.png" title="title-2" width="200" /> 
</p>

train to test split 134:66. No of Hidden neurons:100
Accuracy on test set: 98% , F1 score:0.98, recall: 0.98, precision: 0.9825




Throughout the project, I implement the gradient descent and backpropagation algoritm correctly. Also, loss functions such as  relu, sigmoid, L2_Loss, and gradient descent algos such as rmsprop, adam, and gradient descent with momentum has been implemented from scratch to compare the results which shows that adam works the best among all of them, as expected. 


