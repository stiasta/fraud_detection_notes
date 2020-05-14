# Notes on Fraud Detection and Explainable AI
## Fraud Detection
### Notes
_Electronic Fraud_ is classified into two types of categories:
  - _Direct fraud_
    - For example: Money laundering, Salami technique, Employee embezzlement
    
    
  - _Indirect fraud_
    - For example: malware, phishing, identity theft
    
#### Direct Fraud
##### Money laundering
Converting illicit/illegal money into less suspicious money. This is done to conceal the source of where the money comes from. One technique is to transfer money to multiple accounts using complex transactions. 

##### Salami technique
Transfering a miniscule amount of money from a great amount of customer accounts, using f.ex. insiders in a bank.

#### Indirect Fraud 
##### Identity theft
Someone gains access to personal information to further gain access to services in for example banks.


### Resources
### Articles
- [Dzomira, Shewangu. (2015). Cyber-banking fraud risk mitigation - Conceptual model. Banks and Bank Systems. 10. 7-14.](https://www.researchgate.net/publication/282281102_Cyber-banking_fraud_risk_mitigation_-_Conceptual_model)
  - The aims for the article is to:
    - Critically review the forms of cyber banking fraud risks exposed in the financial sector. 
    - To propose a cyber-banking fraud risk ma- nagement model. 
 - [Application of Credit Card Fraud Detection: Based on Bagging Ensemble Classifier](https://www.sciencedirect.com/science/article/pii/S1877050915007103)

## Explainable AI

### Notes
#### When

#### Shapley values
[Wikipedia definition]()
Rettferdig fordeling av bidrag til prediksjon fra maskinlæringsmodell etter innsatts fra egenskapene (variabler, features)
-> forklarer avvik fra gjennomsnittet
-> Sum of shapley values is prediction

#### [Contrafactual explanations](https://christophm.github.io/interpretable-ml-book/counterfactual.html)
- Can be hard to automatically generate based on a prediction with a big number of features



#### LIME: Local interpratable model agnostic explenations
(not recommended by one lecturer -> why?)

### Unsorted
- Shapley values
- Lime 
- Mutual information (NN)
- Kontrafaktisk forklaring

### Books
- [Interpretable Machine Learning: A Guide for Making Black Box Models Explainable, by Christoph Molnar ](https://christophm.github.io/interpretable-ml-book/)

### Articles, Reports, Books
- https://www.darpa.mil/program/explainable-artificial-intelligence
- [NTNU AI Lab project - EXAIGON: New project on explainable artificial intelligence](https://www.ntnu.edu/ailab/news)

### Tools
- [Captum - Model Interpretability for PyTorch](https://captum.ai/)
- 

### Podcast episodes

- https://twimlai.com/twiml-talk-147-data-innovation-ai-at-capital-one-with-adam-wenchel/
- https://twimlai.com/twiml-talk-73-exploring-black-box-predictions-sam-ritchie/
- https://twimlai.com/twiml-talk-60-fighting-fraud-machine-learning-shopify-solmaz-shahalizadeh/

### Live events

- 14.mai.2020 Kl. 09:00–10:30 Tekna: Forklarbar Kunstig intelligens https://www.tekna.no/kurs/forklarbar-kunstig-intelligens--xai-39856/

### Companies that work in this area
- https://www.sintef.no/en/explainable-ai/

### Other sources
- Kaggle competition https://www.kaggle.com/mlg-ulb/creditcardfraud

## ML Ops
### Tools 
- [MLFlow](https://mlflow.org/)
- [Pachyderm](https://pachyderm.io/)
- [Kubeflow](https://www.kubeflow.org/) (Does not support pytorch yet)

