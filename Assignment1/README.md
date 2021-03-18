# DMW-Assignment1
6th semester DMW Assignment-implementation of generalisation ability of svm based on markov sampling
members:


iit2018117 (Palak Mittal)


iit2018119 (Nehal Singh)


iit2018187 (Abhishek Kumar Gupta)


iit2018191 (Puja Kumari)

iit2018195 (Prabha Kumari)

# how to use that code 

1. open SVM_MARKOV.ipynb in google colab 

2. upload the dataset Magic.csv

3. run block wise

4. you will get the result

# Abstart:
We introduce a new Markov sampling algorithm for SVMC
to generate u.e.M.c. samples from Magic dataset.

# Algorithm
![image](https://user-images.githubusercontent.com/47221030/111444692-a74db600-8730-11eb-89df-4bf969cfb863.png)


# dataset
magic dataset

description of column

 1   fLength     19020 non-null  float64
 
 2   fWidth      19020 non-null  float64
 
 3   fSize       19020 non-null  float64
 
 4   fConc       19020 non-null  float64
 
 5   fConc1      19020 non-null  float64
 
 6   fAsym       19020 non-null  float64
 
 7   fM3Long     19020 non-null  float64
 
 8   fM3Trans    19020 non-null  float64
 
 9   fAlpha      19020 non-null  float64
 
 10  fDist       19020 non-null  float64
 
 11  class       19020 non-null  object
 
# result
![image](https://user-images.githubusercontent.com/47221030/111444228-2a224100-8730-11eb-8dc3-2cd53b0165ea.png)


mean misclassification rate for random sample with std (21.297318611987382, 0.2561270889440842)

![image](https://user-images.githubusercontent.com/47221030/111444299-3a3a2080-8730-11eb-8141-fe30ac975930.png)


mean misclassification rate for markov sample (21.04968454258675, 0.24574694356243504)

# refrence

[1] J. Xu et al., "The Generalization Ability of SVM Classification Based on Markov Sampling," in IEEE Transactions on Cybernetics, vol. 45, no. 6, pp. 1169-1179, June 2015, doi: 10.1109/TCYB.2014.2346536.
