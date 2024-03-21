# End-to-end-ML
Detailed overview of creating and deploying an ML pipeline leveraging a Microservice based architecture.

## Project Description
Building a machine learning pipeline that is effective and relaiable can be a challenging task. One of the critical challenges is data leakage, where information from the future or target variable is inadvertently leaked into the training data, leading to over-optimisitic model performance metrics. Another challenge is deploying the final model for real world use, which require integrating the model into an existing system and ensuring consistent performance over time.

This project will provide an end-to-end process to address these challenges, from building to deploying machine learning models. This pipleine is designed to prevent data leakage and generate an automatic report for each run. Then, these model deploys as an API tha can be used in a web app. This approach is to make model deployment more efficeint and more manageable. It can be applied in a microservice architecture. Few Interesting getaways from this project:
- ML pipeline that prevents data leakage and generates a report.
- Microservice architerture approach consists of Authentication, Machine Learning and Web App Service.
- Consider a security with authentication and hiding credentials.


