Interpretability also popularly known as human-interpretable interpretations (HII) of a machine learning model is the extent to which a human (including non-experts in machine learning) can understand the choices taken by models in their decision-making process (the how, why and what).
 The higher the interpretability of a machine learning model, the easier it is for someone to comprehend why certain decisions or predictions have been made. A model is better interpretable than another model if its decisions are easier for a human to comprehend than decisions from the other model. # Atmosphere

Goal: create and implement metrics to measure Transparency and Trustworthiness

## Motivation
(5) With the application of ML and DL in more critical areas such as medicine, criminal justice and financial applications the inability to understand these models is a problem.

(2) Providing equality: example, an algorithm to help make hiring decisions or criminal justice should not only optimize accuracy but also optimize ethics and justice. How to optimize areas that we can not measure?

(2) Example: A model for predicting the probability of death of a patient with pneumonia is described in (5), this model said that a patient had a lower probability of death if he had asthma. That is, the model felt that if a patient had asthma, then he had less chance of dying and therefore a less aggressive treatment can be done. In fact those who have asthma already have access to a more aggressive treatment, so the model had a lower chance of death due to the treatment that is already being done and not due to the presence of asthma.

(2) Adversarial attacks are a reality, both for image classification and for other cases, as for example credit-seekers may take certain actions before asking for credit to maximize their chances of getting more credit.

(2) New law in the European Union (2016) proposes the right of explanation for users. (5) discusses the tradeoff between accuracy and interpretability / ease of understanding the model for medical cases. They suggest a model (GA²M) that is state of the art in the problem of classifying as low-risk or high-risk cases of pneumonia while being interpretable, modular and editable. The author cites a case in which a neural network had an accuracy of 86% and a logistic regression of 77% was used because they considered the use of neural networks very "risky" for real cases. For greater interpretability tried rule-base learning (SVM and boosted trees were not common, and random forests did not exist), one of the rules was temAsthma (x) -> lower risk of death. This pattern actually exists in the data but should not be followed. The decision not to use neural networks was not because of the difficulty of containing this pattern of appearing in the data, but rather because of the difficulty of understanding how the model works, it is difficult to know what other problems may be occurring.


## Interpretability

Interpretability also popularly known as human-interpretable interpretations (HII) of a machine learning model is the extent to which a human (including non-experts in machine learning) can understand the choices taken by models in their decision-making process (the how, why and what).
 The higher the interpretability of a machine learning model, the easier it is for someone to comprehend why certain decisions or predictions have been made. A model is better interpretable than another model if its decisions are easier for a human to comprehend than decisions from the other model. 



## Trustfulness




## Transparency




## Fairness



## Awareness



## References

