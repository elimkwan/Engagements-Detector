# Analysis Psychological Distress and Conversational Engagements with Supervised Domain Adaptation
Psychology studies indicated that distress have important implications on people’s engagement in conversation. 
However, in today's machine learning literature, most of the research focused on using low-level body language for automatic detection of signs of distress. 
Yet, one challenge in developing a model for detecting abstract affective status (such as conversational engagement) is that it requires a lot of qualitative data.
It would be intriguing to understand psychiatry topics through examining knowledge learnt from pre-trained machine learning models. 
In particular, we would like to investigate the correlation between high-level behaviour features and distress, 
which could potentially aid the development of distress classifiers. 
Therefore, we have proposed a framework for investigating conversational engagement and distress as a novel application of supervised domain adaptation. 
The framework transfers the knowledge learnt from students engagements in the e-learning environment (source domain) to participants engagements 
in well-being interviews (target domain). We have developed our e-learning engagement detector and generated an annotation guide to obtained engagement labels 
for the target domain. Our proposed e-learning engagement detector has successfully attained a high accuracy and 
F1 scores of 93.57\% and 0.93, which is 7.14\% and 6.45\% higher than the baseline. 
Moreover, using only 188 input tensors for training a model of 0.69M parameters, our transfer learning module achieved 
a reasonable accuracy and F1 of 62.50\% and 0.64. Utilising the conversational engagement detector developed, we showed that 
engagement appeared to be correlated to an individual's distress status. Finally, we hoped that our findings would assist the development 
of higher performance distress classifier.

Please refer to the `report.pdf` for more details.
