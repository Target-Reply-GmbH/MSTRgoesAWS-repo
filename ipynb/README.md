This Notebook has been implemented in AWS SageMaker Studio. AWS is acloud machine-learning platform that helps users in building, training, tuning and deploying machine-learning models in a production-ready hosted environment.
### Why do we need AWS SageMaker?
- All ML components are stored in one place
- Highly scalable/High data security
- High-performance model building /training/deploying – pay as you use
- Control & maintain uptime
More information and advantages about AWS SageMaker can be found here [AWS SageMaker Homepage](https://aws.amazon.com/sagemaker/) 

Data Wrangling and Data Preparation partly has been done by using Data flow in the SageMaker Studio.

### Use Case Description
Goal: Finding out which countries have similar patterns regarding Covid-infection cases, deaths, vaccinations and GDP during the pandemic time.
We used the K-means algorithm to solve this. "K-means algorithm is simple algorithm capable of clustering dataset very quickly and efficiently"
Data source is based on [Our World in Data Covid Data] https://ourworldindata.org/coronavirus-source-data 
Unlike the ETL part, the ML part focused more on aggregated (static) data like confirmed cases, vaccinations until the observed date. (a snapshot) 
The raw dataset is stored as a CSV file in one AWS S3 bucket. The model was built, trained, and deployed in AWS SageMaker Studio. 
The Clustering result is stored as a CSV file in S3 bucket and visulized in the MSTR dossier.  
