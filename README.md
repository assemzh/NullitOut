# NullitOut

## Abstract:

Machine learning models can learn patterns in biased data and magnify the existing social inequality when they are used in real-world settings. In this project, we replicate Iterative Null-space Projection (INLP), a novel method for removing information from neural representations Ravfogel et al. 2020, for the purpose of bias mitigation in text classification. The method is based on repeated training of linear classifiers that predict a certain property, followed by projection of the representations on their null-space so that the classifiers become oblivious to that target property. We also improve the paper’s results by applying the method on toxicity classification of text comments. The goal is to remove protected features of target property in the classifier, without sacrificing the accuracy of toxicity classification.

We focused on three bias classes: gender bias, racial bias, and religious bias. The results show that the method can be successfully applied to gender and racial bias mitigation in toxicity classification.

### Religion WorldCloud:
![religion](https://user-images.githubusercontent.com/50063452/121807351-b93ae880-cc8e-11eb-8716-071536bdf439.png)

### Gender WorldCloud:
![gender](https://user-images.githubusercontent.com/50063452/121807375-d2439980-cc8e-11eb-9ecb-710f6e7b9e5c.png)

### Race WorldCloud:
![race](https://user-images.githubusercontent.com/50063452/121807405-f1422b80-cc8e-11eb-8bc1-5bfff46025ba.png)

## Results:

![alt text](https://github.com/assemzh/NullitOut/blob/main/gender/plots/gender.gif)

![alt text](https://github.com/assemzh/NullitOut/blob/main/race/plots/race.gif)

![alt text](https://github.com/assemzh/NullitOut/blob/main/religion/religion.gif)
