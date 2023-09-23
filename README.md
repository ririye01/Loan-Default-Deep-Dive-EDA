# Loan Default Deep Dive Exploratory Data Analysis

See `main.ipynb` for full analysis.
## **1.1: Dataset Overview**

The "Loan Default Dataset" <a href="https://www.kaggle.com/datasets/yasserh/loan-default-dataset">on Kaggle</a> offers a comprehensive view of past data on loan borrowers. This dataset contains several important attributes from fundamental borrower demographics such as gender and age, to more detailed financial markers like debt-to-income and loan-to-value ratios. Originating from real loan applications, this dataset offers a blend of borrower-specific details, loan purpose, and other influential parameters that might affect the chance of a borrower defaulting on a loan. While Kaggle does not state much about the origins of this dataset, and because this data contains very real information about loan borrowers; we believe it is likely that the dataset was put together by leaders in the financial industry, pseudonomynized for privacy and legal reasons, and distributed with the intention of enabling data scientists in the public to create a machine learning model that outperforms their current strategies for predicting loan defaults. Such a strategy is smart, because it allows for leading banks and lending institutions to not have to invest money in a data science team that fails to deliver successful ROI.

Investing in a data team is risky and expensive. According to the <a href="https://www.datascience-pm.com/project-failures/">Data Science Process Alliance</a>, around only 20% of analytics projects deliver successful results, and only around 15% of machine learning models make it to production. Because of pessimistic trends such as these, it makes sense that these leading banks and lending institutions in the financial industry would look for a more risk-averse option by releasing a dataset to the public. At that point, they can then potentially pay someone who built a model that outperforms what they are currently doing, or they can even use a machine learning model that someone releases to the open-souce community from this dataset.

## 
## **1.2: Purpose of Data Collection**

The primary motive behind assembling this dataset was likely the financial sector's persistent challenge with loan defaults. According to page 4 of a report about <a href="https://www.mckinsey.com/~/media/mckinsey/industries/financial%20services/our%20insights/ai%20powered%20decision%20making%20for%20the%20bank%20of%20the%20future/ai-powered-decision-making-for-the-bank-of-the-future.pdf">AI-powered decision-making for banks</a> from McKinsey & Co., with a revenue structure leaning heavily on loan interests, it's essential for lending institutions to ensure expected returns on loans. Loan defaults severely erode revenues, and, in massive scales, can threaten <a href="https://www.fdic.gov/bank/historical/history/3_85.pdf">the entire banking system's stability</a> according to the FDIC on page 29. Therefore, this dataset was developed to aid banks and similar institutions in foreseeing potential defaults, providing them with an analytical edge to make more informed lending choices.

## **1.3: Prediction Task & Stakeholder Interest**

The intention of the Kaggle dataset being released is to determine the likelihood of a borrower defaulting on their loan. Knowing the tendencies of other borrowers in the past, banks can then pre-emptively decide whether or not to approve a borrower's loan application. Rejecting applicants who will likely default on their loan based on previous evidence of borrowers with similar attribute variables. By understanding the factors that contribute to loan defaults, banks and lending institutions can make better-informed decisions, tailor products, or adjust strategies based on these insights.

## **1.4: Algorithm Performance Expectation for Profitability**

In order for this task to deliver successful ROI, a classification algorithm would need to gain deeper, more insightful correlations with loan defaults. The algorithm's success in predicting loan defaults using all the variables in the dataset must be superior in accuracy, time efficiency, and scalability compared to current methods being used right now for it to be deemed beneficial. Simply put, a useful algorithm would be one that not only predicts loan defaults with high accuracy but does so faster and more reliably than current banking practices. Such an algorithm would offer these stakeholders a genuine edge in decision-making, risk management, and strategic planning.
