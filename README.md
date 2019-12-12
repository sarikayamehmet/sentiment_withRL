# sentiment_withRL
Sentiment Analysis Using RL

We develop a new model combining the Reinforcement Learning (RL) method and the supervised NLP method to predict the sentiment. 
We formulate the task of feeling analysis as a sequential decision-making process: current decisions (ie feeling) in a sentence influence the following decisions (feelings) that can be naturally dealt with by the political gradient method (Sutton et al. 2000). Since we cannot predict mood until the end of the sentence, we use the late reward to guide the policy process for the problem. 
We calculate the reward on the basis of a controlled learning with selected entries of the RL method.

To predict sentence sentiment, we develop a new model that combines reinforcement learning (RL) and NLP methods. 
We formulate the analysis of sentiment as a sequential decision-making process: 
current decisions (that is, in one sentence) affect the following decisions (sentiments) that can be dealt with addressed by the gradient method. 
Even though we can not predict sentiments until reaching end of the sentence, we are using delayed rewards to guide the process of learning of policy. 
We calculate the reward based on learning, which is controlled by inputs selected from the RL method.
