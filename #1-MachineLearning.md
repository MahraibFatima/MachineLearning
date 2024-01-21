# **Machine Learning:**
Machine learning is about creating systems that can automatically learn and improve from experience, providing the capability to adapt and perform tasks without being explicitly programmed for each specific task.

Subfields of Machine learning:
- Supervised learning 
- Unsupervosed learning
- Reinforcement learning
  
# Supervised learing:
  Supervised learning is when we give our learning algorithm the right answer  for each example to learn from.
    
  Input -> output [label]
  
  Examples:
  |Input          | Output [labels]      |  Applications|
  | -------           |    -----------           | ---------------  |
  |English            |  Spanish                 |  Machine translation|
  |Email              |  Spam? [ 0 or 1]          |  Spamming filter|
  |Audio              |  Text                    |  Speech recognition| 
  |Ads,user info      |  Click? [0 or 1]          |  Online Aadvertisements or surveys|
  |Image [phone]      |  Defect? [0 or 1]          |  [Visual inspection [**Visual inspection** examines objects or systems for defects, damages, and other issues.] ](https://facilio.com/blog/visual-inspection/) |

Both **Regression and Classification algorithms** are used to predict in Machine learning and work with labeled datasets.

[**Regression:**](https://www.simplilearn.com/regression-vs-classification-in-machine-learning-article#regression_in_machine_learning_explained)
  Regression algorithms help predict continuous variables.
  
[**Classification:**](https://www.simplilearn.com/regression-vs-classification-in-machine-learning-article#classification_in_machine_learning_explained)
Classification is an algorithm that finds functions that help divide the dataset into classes based on various parameters.

|Regression          |  Classification|
| -------           | ---------------  |

| ![img](imgs/1-MachineLearning/SupervisedLearningHousePredictionRegressionExample.png) |  ![img](imgs/1-MachineLearning/ClassificationExample.png)     |

# Unsupervised learing:
  Find interesting data patterns in your unlabeled data.
  
   [*Clustering*](https://www.geeksforgeeks.org/clustering-in-machine-learning/) is grouping of similar data points together. Clustering is basically a collection of objects on the basis of similarity and dissimilarity between them. 
   For example: 

  | DNA microarray |  Google News | tech ppl grouping |
  | --------       | ------------ | -------------- |
  | ![img](imgs/1-MachineLearning/DNA_microArray.png)|  ![img](imgs/1-MachineLearning/Google_news.png) | ![img](imgs/1-MachineLearning/grouping-Customer.png) |
  
   [*Anamoly Detction*](https://www.techtarget.com/searchenterpriseai/definition/anomaly-detection) Anomaly detection is the process of identifying data points, entities or events that fall outside the normal range. It msotly consist to usual data points.
   
   [*Dimensionality Reduction*](https://machinelearningmastery.com/dimensionality-reduction-for-machine-learning/) Dimensionality Reduction compress data using few numbers. Dimensionality reduction refers to techniques that reduce the number of input variables in a dataset.
   
# Reinforcement learning:
In reinforcement learning, an agent takes actions within an environment, and based on those actions, it receives feedback in the form of rewards or penalties. The goal of the agent is to learn a strategy or policy that maximizes the cumulative reward over time.

[**Key components of reinforcement learning:**](https://www.javatpoint.com/reinforcement-learning#Terms)

- **Agent:** The entity that makes decisions and takes actions within the environment.

- **Environment:** The external system with which the agent interacts. It provides feedback to the agent based on the actions taken.

- **State:** The current situation or configuration of the environment that the agent perceives.

- **Action:** The set of possible moves or decisions that the agent can make.

- **Reward:** A numerical value that indicates the immediate feedback the agent receives after taking an action in a particular state. The goal of the agent is to maximize the cumulative reward over time.



  
