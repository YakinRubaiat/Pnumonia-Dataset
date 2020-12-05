Resnet101 model male(5000) female(4000) of RSNA (both pa and ap): 
      class: lung opacity : 4400, normal: 2200, not normal:2200
      ![resnet101 male female(total) rsna equal balance binary class test acc 71%, training 86%](https://user-images.githubusercontent.com/52566550/100654194-a8222e00-3373-11eb-9507-d866d02258fb.png)
      

Resnet101 model on male(7547) female(5653) rsna data
      class: lung opacity : 4400, normal: 4400, not normal:4400
      ![resnet101 male female(total) rsna equal balance 3 classes test acc 53%, training 83%](https://user-images.githubusercontent.com/52566550/100654220-afe1d280-3373-11eb-8fb2-595dd80bd21a.png)
      
Resnet101 on male female  rsna(only PA) 
       class: lung op-1000, normal-500, not normal-500,  validation accuracy and loss decreasing, model underfits.
      --instead of rmsprop, if we use adam, training acc is less, validation acc and loss increases and decreases (fluctuates)
      ![resnet101 male female pa rsna  25 ,384,  10 epochs ,  auc train test curve (class-not normal 500, normal 500, lung op-1000)](https://user-images.githubusercontent.com/52566550/100654416-f59e9b00-3373-11eb-9eea-0f70447ee94b.png)
      
      
   class: lung op-1000, normal-500, not normal-1000
      model underfitting, 73% test, 79% training acc, validation curve doesnt fluctuate.
      
   ![resnet101 male female pa rsna normal 500, not normal 1000, lung 1000, test acc 73%, training 79% curve 10 epochs, rmsprop dropout  25 , 384](https://user-images.githubusercontent.com/52566550/101233931-82838480-36e5-11eb-8892-febed48ec7ee.png)

 

      
