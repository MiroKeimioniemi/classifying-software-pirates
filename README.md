# Classifying Software Pirates in the Music Production Software Industry

Below is a short excerpt of the Classifying Software Pirates in the Music Production Software Industry.pdf report, briefly summarizing the rationale, methodology and results of the project.

## Introduction

This project attempts to dive deeper into the dataset used for the report [“The Pricing of Digital
Goods in the Music Production Software Industry”](https://users.aalto.fi/~keimiom1/portfolio/writing/the-pricing-of-digital-goods-in-the-music-production-software-industry.html) to try classify people into those who have
pirated music production software and to those who have not based on a variety of features. This
could then be used to explore the factors driving people into software piracy to gain more insight
into this prominent modern phenomenon that extends to all online markets. This information can
unlock economic insights into people’s online behavior and help software companies maximize their
profits by conducting appropriate customer segmentation, which would likely benefit the customers
as well in situations where they have not previously been able to afford the products. 

## Conclusion
Two machine learning models, DecisionTreeClassifier and LogisticRegression were developed to
classify software pirates using demographic and similar, one-hot encoded, categorical data. Their
performance characteristics were practically identical and thus LogisticRegression was selected due
to its better interpretability, which poses that the factors most correlating with online piracy are its
ease and the age and residence region of the person, both of which usually directly affect their
disposable income. This implies that there might still be more room for further market segmentation
in the form of, for example, country-specific pricing and student discounts.

The selected Logistic Regression model has an accuracy of 0.729729 and an F1 Score of 0.741379,
which is quite good for a dataset this small, biased and noisy. This was enough to reveal and rank
overall trends in terms of their approximate influence on the amount of piracy, but the accuracy
would be quite poor for a classification system that would mislabel over one fourth of the people
considered, which is something to be very careful about. Hence, this project’s focus on the predictive
features over the predictions themselves. 
