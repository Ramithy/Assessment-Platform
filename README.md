# Assessment-Platform
Project Description
The Assessment Platform is a comprehensive tool designed to assess employee skills and knowledge. This platform supports various assessment modules, automates grading and feedback, and provides detailed analytics to HR and management teams for evaluating employee performance.

Features
Automated Grading: Uses AWS Lambda to automatically grade assessments and provide feedback.
Detailed Analytics: Generates reports and analytics for HR and management.
Customizable Assessments: Allows businesses to create tailored assessments.
Integration with HR Systems: Seamless tracking of employee assessment results.
AWS Services Used
Amazon EC2: For hosting and managing the application.
AWS Lambda: For automating grading and feedback.
Amazon RDS: To store assessment data and results.
Amazon CloudWatch: For monitoring performance and providing analytics.
Objectives
Automate the grading process and provide instant feedback.
Generate detailed analytics for HR and management teams.
Support customized assessments tailored to specific business needs.
Deployment
The platform is deployed on AWS, utilizing EC2 for hosting, Lambda for automating grading, RDS for database management, and CloudWatch for monitoring and analytics.

Setup Instructions
Clone the Repository:


git clone https://github.com/Ramithy/assessment-platform.git

Navigate to the Project Directory:


cd assessment-platform

Install Dependencies:

Follow the instructions in the INSTALL.md file to install necessary dependencies.

Deploy on AWS:

Launch an EC2 instance and configure the environment.
Set up RDS for the database.
Configure Lambda for automated grading.
Monitor the platform using CloudWatch.
