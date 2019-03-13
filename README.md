# Atmosphere

Goal: create and implement metrics to measure Transparency and Trustworthiness

## Motivation
With the application of ML and DL in more critical areas such as medicine, criminal justice and financial applications the inability to understand these models is a problem.

Providing equality: example, an algorithm to help make hiring decisions or criminal justice should not only optimize accuracy but also optimize ethics and justice. How to optimize areas that we can not measure?

Example: A model for predicting the probability of death of a patient with pneumonia is described in, this model said that a patient had a lower probability of death if he had asthma. That is, the model felt that if a patient had asthma, then he had less chance of dying and therefore a less aggressive treatment can be done. In fact those who have asthma already have access to a more aggressive treatment, so the model had a lower chance of death due to the treatment that is already being done and not due to the presence of asthma.

Adversarial attacks are a reality, both for image classification and for other cases, as for example credit-seekers may take certain actions before asking for credit to maximize their chances of getting more credit.

New law in the European Union (2016) proposes the right of explanation for users. (5) discusses the tradeoff between accuracy and interpretability / ease of understanding the model for medical cases. They suggest a model (GA²M) that is state of the art in the problem of classifying as low-risk or high-risk cases of pneumonia while being interpretable, modular and editable. The author cites a case in which a neural network had an accuracy of 86% and a logistic regression of 77% was used because they considered the use of neural networks very "risky" for real cases. For greater interpretability tried rule-base learning (SVM and boosted trees were not common, and random forests did not exist), one of the rules was temAsthma (x) -> lower risk of death. This pattern actually exists in the data but should not be followed. The decision not to use neural networks was not because of the difficulty of containing this pattern of appearing in the data, but rather because of the difficulty of understanding how the model works, it is difficult to know what other problems may be occurring.


## Interpretability
Interpretability also popularly known as human-interpretable interpretations (HII) of a machine learning model is the extent to which a human (including non-experts in machine learning) can understand the choices taken by models in their decision-making process (the how, why and what).
 The higher the interpretability of a machine learning model, the easier it is for someone to comprehend why certain decisions or predictions have been made. A model is better interpretable than another model if its decisions are easier for a human to comprehend than decisions from the other model. 
 
            



## Trustfulness
“I have a model with 90% accuracy” is not sufficient information.
Trying to depend on a model for certain problems, relying solely on these metrics, does not guarantee great confidence. Especially when trying to have its model presented to lay people on the subject in which they are not aware of such metrics.




## Transparency
Increasingly, the concept of Machine Learning and Deep Learning is applied to many problems, but often the problem is very complex and so the linear model is not a solution, starting with more robust but increasingly black solutions, transparency serves with this intention to help observe and analyze the confidence in the model based on its outputs.
Evaluate and validate any point of the data in order to analyze if the model is having the expected behavior and made the decisions consistent with the problem





## Fairness



## Awareness
Users, owners, designers ... should be aware of the possible bias present in the models and of the possible giving that this bias can bring to society. "What am I buying?"


## References
* [LIME](https://github.com/marcotcr/lime)
* [SHAP](https://github.com/slundberg/shap)
* [Interpretable-ml-Book](https://github.com/christophM/interpretable-ml-book)
