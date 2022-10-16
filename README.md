# Hope-Speech
Hope Speech Detection : detecting hope comments using binary classification. 


With the expansion of the Internet,social media there has been huge growth all over the world in the number of marginalised people looking for support online. Comments/posts on online social media have been studied to find and stop the spread of negativity using methods such as hate speech detection. We should  work towards spreading positivity instead of suppressing an individual’s freedom of speech by removing negative comments. Therefore, we move our focus towards hope speech.

## What is Hope Speech ?
We define hope speech as the speech that spread positivity, inspire and motivate people. Here it’s about social media, specifically YouTube comments. Hope speech can encourage people to delve deeper into their desired objectives and become better individuals. Our work aims on solidifying this approach towards criticism by moving on from derogatory remarks to comments that boost confidence, gives support.

## Dataset availability/description: 
We received our dataset from [Hope Speech Detection for Equality, Diversity, and Inclusion -ACL 2022 competition](https://competitions.codalab.org/competitions/36393). Dataset description:

![description_dataset](https://github.com/NiranjanMeghwal/Hope-Speech/blob/main/src/1.JPG)

## Project workflow:

![work_flow](https://github.com/NiranjanMeghwal/Hope-Speech/blob/main/src/2.JPG)

## Classification:

we concluded that using binary classification we can seprate hope and hate comments easily, we used the following methods for binary classification:
* Bi-LSTM : 
 
 ![bilstm](https://github.com/NiranjanMeghwal/Hope-Speech/blob/main/src/3.JPG)

* TF-IDF vectors + SVM : 

![tf-idf](https://github.com/NiranjanMeghwal/Hope-Speech/blob/main/src/4.JPG)

## Results: 

![results](https://github.com/NiranjanMeghwal/Hope-Speech/blob/main/src/5.JPG)

## Conclusion: 

* During these unprecedented times, there is a need to detect positive, supportive content.
* We worked towards encouraging positivity in form of hope speech to induce compassion and acceptable social behaviour.
* We have used two classifiers that are TF-IDF vectors + SVM and BiLSTM.
* We also conclude that in this case the TF-IDF vectors + SVM model have given better results than BiLSTM.

