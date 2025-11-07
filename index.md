**Name & Email**  
Ethan Flores — etflores@ucsd.edu

**Section & Mentor**  
Section: B02  
Mentor: Kyle Nero & Daniel Mathew

---

## Quarter 2 Project Proposal Brainstorm

**What is the most interesting topic covered in your domain this quarter?**

This quarter, the most interesting topic in our domain would be the experimenting with different machine learning and deep learning models to categorize the “category” column in our transaction dataset. I began with classical approaches such as logistic regression and random forests, then transitioned to deep learning models, including neural network architectures and transformer-based models from platforms like Hugging Face. Comparing these approaches helped me understand how model complexity, representation learning, and domain-specific architectures affect classification performance in real-world financial data.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  

For Quarter 2, I’d like to explore how our transaction dataset can be used to estimate consumer credit risk. Instead of only classifying categories, the focus would shift toward identifying behavioral and spending patterns that may signal financial risk. We would use financial data like transaction amounts, category types, debit versus credit activity, account balances over time, and individual credit scores to construct features that reflect a consumer’s financial stability. Then, incorporating machine learning, we can estimate the probability that an individual will become delinquent or showcase high credit risk based on these behavioral features. 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  

One potential change I'd like to make to the apporach taken in my current Quarter 1 project would be to incorporate domain-specific NLP models that have been pre-trained on financial text, such as FinBERT or FinancialBERT. So far, we have just used generalized NLP models like BERT or LLM-based architectures that weren't optimized for the current financial consumer data are currently using. Testing these models would allow us to captured the nuanced languages used in the datasets that the generalized model won't be able to pick up on.

**What other techniques would you be interested in using in your project?**  

I’d be interested in experimenting with alternative classical models such as Support Vector Machines (SVMs), Naive Bayes classifiers, and K-Nearest Neighbors. These approaches can serve as strong baselines for comparison against more complex deep learning architectures. Deep models can capture complex relationships but can often overfit and focus too much on the noisy data points making their performance be way lower compared to simple models which can generalize better.
