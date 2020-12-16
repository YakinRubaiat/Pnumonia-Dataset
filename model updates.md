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
   
   
 resnet101 on rsna ( male-female pa)
 class: lung op : 1076, normal: 1076
 train validation curve:
![resnet101 male female rsna pa 224  25 10 epochs normal 1076 pneumonia 1076 split 0 2 train auc 90% test auc 55% ](https://user-images.githubusercontent.com/52566550/102318028-d83c1480-3fa2-11eb-9a47-1e5f581fb242.png)

train auc score: 90%
local test data auc score: 55%

male pa: class: lung opacity: 620, normal: 620
train-validation curve:
![resnet101 male pa rsna normal  620 and pneumonea 620 10 epochs train auc 89% test auc 66%](https://user-images.githubusercontent.com/52566550/102318238-3668f780-3fa3-11eb-9f9c-d5032bf96a58.png)

train auc score: 89%
local test data auc score: 66%

female pa: lung opacity: 400, normal: 400
train-validation curve:
![resnet101  female rsna pa 224  25 10 epochs normal 400 pneumonia 400 train auc 93% test auc 55% ](https://user-images.githubusercontent.com/52566550/102318408-792acf80-3fa3-11eb-8190-f56e3f426397.png)


train auc score: 93%
local test data auc score: 55%


Densenet121 on rsna ( male-female pa)
 class: lung op : 1076, normal: 1076
 train validation curve:
![densenet121 male female rsna pa 224  25 10 epochs normal 1076 pneumonia 1076 split 0 2 train auc 89% test auc 59% ](https://user-images.githubusercontent.com/52566550/102318532-aaa39b00-3fa3-11eb-98ae-82927e402580.png)

train auc score: 89%
local test data auc score: 59%

male pa: class: lung opacity: 620, normal: 620
train-validation curve:
![densenet121 male pa rsna normal 620  and pneumonea 620 ( 20 split) 10 epochs train auc 90% test auc 64%](https://user-images.githubusercontent.com/52566550/102318570-bb541100-3fa3-11eb-8169-faeaeb3223e5.png)

train auc score: 90%
local test data auc score: 64%

female pa: lung opacity: 400, normal: 400
train-validation curve:
![densenet121 female pa rsna normal and pneumonea 10 epochs train auc 90% test auc 55%](https://user-images.githubusercontent.com/52566550/102318587-c4dd7900-3fa3-11eb-858d-9fd1ed82d54e.png)


train auc score: 90%
local test data auc score: 55%


  


 

      
