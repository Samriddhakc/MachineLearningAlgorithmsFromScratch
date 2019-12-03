This project is an attempt to code Support Vector Machine from scartch.

Until now, only the case for binary classifier has been taken into account with the following loss function in mind: 

<p float="left">
  <img width="586" alt="LossFn" src="https://user-images.githubusercontent.com/26017262/70012200-bf9cc000-1541-11ea-8dd2-42534c52de7a.png">
</p>

Note, this loss function is trying to enforce an margin such that if y*f(x)>=1 then the loss is 0. So, the labels are -1 and 1. 

Results: 
  <img width="586" alt="LossFn" src="https://user-images.githubusercontent.com/26017262/70012200-bf9cc000-1541-11ea-8dd2-42534c52de7a.png">
 <p float="left">
  <img title="LossGraph" width="517" alt="LossGraph" src="https://user-images.githubusercontent.com/26017262/70012535-a1838f80-1542-11ea-902a-7a5b5031436a.png">
 </p>

Results: 

<p float="left">
   <img width="350" alt="BeforeSeparation" src="https://user-images.githubusercontent.com/26017262/70012571-c0822180-1542-11ea-82be-0f94be9f5487.png">
  <img width="350" alt="LargeMarginClassifer" src="https://user-images.githubusercontent.com/26017262/70012605-d263c480-1542-11ea-8332-277057a0a248.png">
</p>
