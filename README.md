
<img width="600" alt="NLE" src="https://i.imgur.com/488nYbr.jpg">  <img display="inline" width="100" alt="EMNLP" src="https://i.imgur.com/8c0QJBF.jpg">
### To Annotate or Not:question:Predicting Performance Drop under Domain Shift :mag_right:
##### :heavy_check_mark: :page_with_curl: Paper accepted to EMNLP-IJCNLP 2019

## :pill: tldr;
We propose a method that is able to predict the drop in accuracy of a trained model. Our method can predict the drop in accuracy with an error rate as little as 2.15% for sentiment analysis and 0.89% for POS tagging respectively, without needing any labeled examples from the target domain. 

## :small_red_triangle_down: Brief

* In this paper we study the problem of predicting the performance drop of modern NLP models due to domain-shift, in the absence of any target domain labels. 

* We investigate three families of methods (H-divergence, Reverse Classification Accuracy and Confidence measures), show how they can be used to predict the performance drop and study their robustness to adversarial domain-shifts.

* Afterwards we employ those metrics to estimate the performance drop on a new target domain Dt by regressing on those metrics and their associated real performance drop. 

<p align="center"> <img width="400" alt="Approach overview" src="https://i.imgur.com/pmKzp4W.png"> </p>


### Dataset
#### Sentiment Analysis
#### POS Tagging



#### Authors:

Hady Elsahar & Matthias Galle

hady.elsahar@naverlabs.com
