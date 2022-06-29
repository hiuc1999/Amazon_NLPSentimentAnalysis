# Amazon_NLPSentimentAnalysis

### Sentiment Analysis on Amazon Reviews <br />
<img src="https://github.com/hiuc1999/Amazon_NLPSentimentAnalysis/blob/main/image/amazon%20review.jpeg" width="600" height="280"> <br /> 

#### Business Objective
1. Boost Sales by better marketing tatics <br />
2. Improve company’s products & services <br />
3. Track sentiments in real-time <br />
4. Maintain brand preception <br />


#### Data Collection
The dataset is obtained from Kaggle. <br /> 
<br />
<img src="https://github.com/hiuc1999/Amazon_NLPSentimentAnalysis/blob/main/image/Kaggle.png" width="620" height="180"> <br /> 

#### Data Preprocessing
1. Create a binary column and define score > 3 is positive else negative. <br /> 
2. Clean contractions and Define customized stopword list <br /> 
3. Import SnowballStemmer. <br /> 

#### Models Used
1. Naive Bayes (after stratified K-fold cross validation) <br /> 
F1 score: 89.12% <br /> 

2. SGD Classifier (after stratified K-fold cross validation) <br /> 
F1 score: 91.82% <br />
 
3. Transformer from Hugging Face <br />
F1 score: 74.44% <br /> 


