
# Analyzing Traffic Mode Choice Preference

In this project, I aim to evaluate the behavior and factors influencing traffic mode choices (e.g., Bus, Car, Public Transport). Using a dataset of 500+ individuals who regularly commute for work and daily activities, I intend to achieve two goals: first, to visualize key insights from the dataset for a clearer understanding of travel patterns; and second, to build a regression model that identifies the factors influencing mode choice behavior.

So far, I have explored the accuracy of models like Random Forest, K-Nearest Neighbors (KNN), Naive Bayes, Logistic Regression, and Decision Trees to evaluate their performance. I have primarily used Multinomial Logistic Regression now, but in future, I would like to implement Random Forest and Decision Tree models, as they tend to offer improved accuracy, often exceeding 80%. In the meantime, if you have any suggestions or insights regarding this project, I’d love to hear them.

Thank you! — Pial Barua


## Software Acknowledgement

- Jupyter NoteBook
- Google Colaboratory
- MS Excel


## Motivations and Future Plan

- Chittagong city has a diversity of public transport modes. People tend to use public transport frequently due to traffic congestion and the affordability of these modes. However, the tendency to use different modes varies among individuals depending on several factors. For example, the same individual might choose a bus to go to work but prefer a rickshaw for their social life.

- I want to understand this complex behavior first, to work further in future studies. For instance, I would like to explore travel patterns, the accessibility of certain modes, and route adjustments to avoid unnecessary transport while still fulfilling people's needs.



## Some Features

- A heatmap which is useful for clearly identifying the travel mode preferences based on the type of trip and provides an easy comparison with numerical clarity.


  ![Captuarhehre](https://github.com/user-attachments/assets/14a410a5-f002-4405-93b4-426b1645277a)






- This picture below provides a good foundation for understanding the dataset’s overall patterns. The dataset reveals several key insights across different variables.



   ![Capture](https://github.com/user-attachments/assets/eede7ccb-3ba7-46c2-9bf9-d3b80a19aaac)


  


  

- The coefficients show the strength and direction of the relationship between each feature and the target variable (e.g., different travel modes). Features with larger absolute coefficients have more influence on the model's predictions, while smaller values suggest less influence. 



   ![cooof](https://github.com/user-attachments/assets/80c68262-8d2b-4ff8-9799-5280f455737d)








- The graphs display the feature importance for different regular travel modes (Bus, CNG, Car, Laguna, Mahindra, Motorcycle, Rickshaw, Walking, and Others), showing how each feature influences the likelihood of choosing a particular mode of transportation.




   ![describe](https://github.com/user-attachments/assets/684f08c3-df9b-497e-85a4-6faa99aa320b)




## Acknowledgment

- The Dataset was collected and used with permission from Md. Sifat Bin Siraj, School of Transportation and Logistics, Southwest Jiaotong University, China.
- The Actual Dataset was not preprocessed for Machine Learning Algorithm. I preprocessed the whole dataset for this project, and make a lot of changed. Hence the dataset here in the file section will be unique.
- Took some help from Chatgpt, and other AI tools. 


















