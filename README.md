Project Title:
CRM Evaluation

Project Overview:
This research project will consider what are the greatest differentiators between customers and noncustomers? 

This research paper uses three datasets: customer information, noncustomer information, and actions performed by customers and noncustomers.

This project will be divided into modules which align with the CRISP-DM for increased transparency and replicability.
![image](https://github.com/user-attachments/assets/24712c56-fd61-4924-a57b-ef2c0868a337)

Dataset Information 
This research paper uses three datasets: customer information, noncustomer information, and actions performed by customers and noncustomers.
CRISP-DM Process 

Repository Structure 
The structure of this repository is as follows
data/ This folder contains the initial datasets as well as any dataframes generated from the notebooks
output/ This folder contains all model outputs, evaluation metrics, and visualizations generated while running the project
notebooks/ This folder contains the notebooks which contain the code to run the project, the requirements file containing libraries and dependencies, and the Business understanding.md file to provide context.

How to Run the Project 
This project follows the CRISP-DM and notebooks should be run in that order. It is designed to be deployed using AWS Lambda. This project runs using Python 3.12.x and this should be chosen in the Lambda AWS Console

Dependencies 
Dependencies are listed in the requirements.txt file located in the notebooks/ folder

Results and Insights  

This project answers the following questions:
What are the greatest differentiators between customers and noncustomers? 
Using and XGBoost model with backward selection to determine the most significant features, this project demonstrates with 90% test accuracy, and an 83% f1 score 
that the most important features in determining customer conversion are the Alexa Rank, a measure of website popularity, the number of actions performed per user, and the number of deals logged per user in the CRM syst
