This project is an attempt to code Support Vector Machine from scartch.

Until now, only the case for binary classifier has been taken into account with the following loss function in mind: 

<p float="left">
  <img width="586" alt="LossFn" src="https://user-images.githubusercontent.com/26017262/70012200-bf9cc000-1541-11ea-8dd2-42534c52de7a.png">
</p>

Note, this loss function is trying to enforce an margin such that if y*f(x)>=1 then the loss is 0. So, the labels are -1 and 1. 

