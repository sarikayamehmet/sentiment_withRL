# Sentiment Analysis Using RL

To predict sentence sentiment, we develop a new model that combines reinforcement learning (RL) and NLP methods. 
We formulate the analysis of sentiment as a sequential decision-making process: 
current decisions (that is, in one sentence) affect the following decisions (sentiments) that can be dealt with addressed by the gradient method. 
Even though we can not predict sentiments until reaching end of the sentence, we are using delayed rewards to guide the process of learning of policy. 
We calculate the reward based on learning, which is controlled by inputs selected from the RL method.
