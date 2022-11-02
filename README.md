
# MSTRgoesAWS-repo

This is a repo of MSTRgoesAWS Project from Visual Analytics Unit, Target Reply GmbH. It intents to bridge the knowledge gaps among business users, frontend and backend engineers, developers, and DevOps engineers. It also showcase the benefits of using MSTR and AWS to leverage data and get more insights. 

The business Intelligence tool MicroStrategy(MSTR) is a modern, open enterprise platform, which provides consumer-grade BI experiences for every role, on any device, with the platform giving sub-second responses at an enterprise scale. Visual Analytics Unit of Target Reply focuses on using different BI tools, especially MSTR to realize data analysis and visualizations, ultimately supporting clients in their decision making process.      

As a lead cloud computing platform, Amazon Web Services (AWS) provides comprehensive products and services, e.g. Amazon EC2, Amazon Simple Storage Service (S3), Lambda, etc. Cloud computing is becoming more and more prominent thank to its benefits, such as high availability, elasticity, agility, and durability. 

Therefore, the project MSTRgoesAWS aims to combine the most handy functionalities/services of MSTR and AWS together. 

![Screenshot 2022-11-02 at 16 17 52](https://user-images.githubusercontent.com/102745415/199528758-46e54dd9-3c4b-4410-bbbb-5045a945cea9.png)

## Starting Point
In 2020, MSTR BU of Target Reply built a use case to track, analyze and predict global Covid-19 infection, recovery, death and vaccination cases, by means of ETL, ML, MSTR etc. An interactive and user-friendly dossier (dashboard) in MSTR showcases the development of the infection (recovery, death, vaccination) rate overtime, clustered based on geographic locations. 

## Improvement Potentials 
- Source data is not up-to-date
- Automate developing, testing and deployment of application
- Bring in more flexibility and elasticity 

## Project Scope
The following image shows the project scope, which demonstrates four teams, their responsibilities and tools/services involved. 
- ADMIN: adminstration and monitor, including IAM, Authentication and Authorization, Backup, Billing, Security
- ETL: data storage and ETL jobs design using AWS Glue, visualize up-to-dated data in MSTR dossiers
- ML: data wrangling, preparation, building, training and developing the machine learning model by using AWS SageMaker and visualize the clustering result       in MSTR dossier
- DEVOPS:CICD Pipeline to automate the workflow by using AWS CodePipeline
<img width="1312" alt="ProjectScope" src="https://user-images.githubusercontent.com/102745415/199471653-982566e4-efff-4af2-9b44-7492db5349a5.png">

## Repo Structure 
The mono-repo approach is used in this project, i.e., all codebases and files for documentation purposes are kept in this single repository (MSTRgoesAWS-repo).

Besides the main branch, we created three other feature branches based on the teams (ML, ETL, DevOps) so that each team manages its codebase on its own branch. Once the new feature is complete, the feature branch can be merged back into the main branch.
 
In this repo, source code is saved in their respective folders based on file types.

We welcome any questions, feedback, and comments. 
