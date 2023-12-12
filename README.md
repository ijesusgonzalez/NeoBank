# NeoBank
Driving Customer Value by Behaviour Segmentation.
Slide for the presentation: https://www.canva.com/design/DAF2SYuVAtk/ZqleSrT5KM6mECQY4DVodQ/edit?utm_content=DAF2SYuVAtk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Dashboard made in Power BI exported into the PDF.

For our study, we concentrated on a dataset provided by the company, consisting of user information (age, country, currency, subscription plan) and transaction details (amount spent, transaction types, country of transaction, etc).

Our primary goal was to analyze how to transition users from the free 'STANDARD' subscription plan to paid plans like 'PREMIUM' and 'METAL.' To achieve this, we needed to first understand user behavior based on their transactions. To accomplish this, we employed a machine learning model and subsequently utilized the elbow method to determine the optimal number of clusters for grouping users. These clusters were formed based on the average monthly $USD spent and the frequency of transactions.

After establishing these metrics and labeling the clusters, we delved into studying the behavior and plan distribution within each cluster. This enabled us to formulate tailored action plans for distinct groups, such as "Possible Churners," "Average Users," "Traveler Profile," and "Exceptional Users."

Moreover, an ongoing feature development aims to address the unique needs of users labeled as "Traveler Profile." By examining the countries of origin and the destinations visited, this feature has the potential to facilitate targeted action plans or marketing campaigns specific to those countries.

While these steps form the core of our study, it's worth noting that the machine learning model details, the specific features considered, and any encountered challenges contribute crucial nuances to the overall analysis.
