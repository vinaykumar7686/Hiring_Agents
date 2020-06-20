# Hiring_Agents
Prediction Model to identify the right agents to hire based on companies past recruitment data.

# Problem Statement
Your client is a financial distribution company. Over the last 10 years, they have created an offline distribution channel across the country.
They sell financial products to consumers by hiring agents in their network. These agents are freelancers and get a commission when they make a product sale.

# Overview of your client onboarding process

The managers at your client are primarily responsible for recruiting agents. Once a manager has identified a potential applicant he would explain the business 
opportunity to the agent. Once the agent provides the consent, an application is made to your client to become an agent. In the next 3 months, this potential 
agent has to undergo a 7 days training at your client's branch (about sales processes and various products) and clear a subsequent examination in order to become an agent.

#The problem - who are the best agents?

As it is obvious in the above process, there is a significant investment which your client makes in identifying, training, and recruiting these agents. 
However, there are a set of agents who do not bring in the expected resultant business. Your client is looking for help from data scientists like you to 
help them provide insights using their past recruitment data. They want to predict the target variable for each potential agent which would help them identify
the right agents to hire.

# Key Points: The evaluation metric to be used is ROC-AUC.

Data 
Variable	                            Definition

ID	                                  Unique Application ID
Office_PIN	                          PINCODE of Your client's Offices
Applicant_City_PIN	                  PINCODE of Applicant Address
Applicant_Gender	                    Applicant's Gender
Applicant_Marital_Status	            Applicant's Marital Status
Applicant_Occupation	                Applicant's Occupation
Applicant_Qualification	              Applicant's Educational Qualification
Manager_Joining_Designation	          Manager's Joining Designation
Manager_Current_Designation	          Manager's Designation at the time of application sourcing
Manager_Grade	                        Manager's Grade
Manager_Status	                      Current Employment Status (Probation/Confirmation)
Manager_Gender	                      Manager's Gender
Manager_Num_Application	              Number of Applications sourced in the last 3 months by the Manager
Manager_Num_Coded	                    Number of agents recruited by the manager in the last 3 months
Manager_Business	                    Amount of business sourced by the manager in the last 3 months
Manager_Num_Products	                Number of products sold by the manager in the last 3 months
Manager_Business2	                    Amount of business sourced by the manager in the last 3 months excluding business from their Category A advisor
Manager_Num_Products2	                Number of products sold by the manager in the last 3 months excluding business from their Category A advisor
Business_Sourced(Target)	            Business sourced by the applicant within 3 months [1/0] of recruitment
