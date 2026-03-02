D:\MLOPs Course --> Data Science 2026 --> MachinE-LearninG-ProjecT

# MachinE-LearninG-ProjecT
The project includes : Github And Code Set up, Project Structure, Logging And Exception Handling, EDA And Model Training, Data Ingestion, Data Transformation, Model Trainer, Predict Pipeline, Model Deployment


Agenda of Project

1. Set-up Github [For Community].
2. env --> conda create -p venv python==3.12 -y
3. active conda --> conda activate venv/
4. Initialize the git --> git init
5. pip install -e .
6. python setup.py install
7. components in src folder will help to reading a data wtih multiple operations like: EDA, Feature Eng etc.
8. for exception in "src" search """sys library python""".
9. more about EDA and Model Training and more.
10. see output: http://127.0.0.1:5000/predictdata



## Cloud

1. Elastic Beansalk

2. github --> codepipeline --> Elastic Beanstalk

3. Search Elastic Beansalk --> create application --> Application Name --> No any key and Value it's empty by default --> Platform is python --> Application Code Sample application --> Create application --> Creating an env.
   
4.  Search CodePipeline  --> It's for CD Pipeline --> Open it --> create new pipeline  --> Pipeline name --> All as by default  --> next  --> Source  -->  Github  --> Connect to Github  --> Select Reposity  -->  Branch [main]  --> next  --> Build  --> Skil it  --> Next  --> Deploy  --> 1.AWS Elastic Beanstalk  --> 2.Region  --> 3.Application Name  --> 4.Env name  -->  next

5. See in Elastic beanstalk application  -->   Then go back / see Add Deploy Stage:
6. Click Next
7. Final click create Pipeline
8. Think and some time delete app.py file
9. Success..........$
10. Get the URL [[Click on AWS lastik Beanstalk below Deploy then --> Env --> Click URL and /predication also..$]]