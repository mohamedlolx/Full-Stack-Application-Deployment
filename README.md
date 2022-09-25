# Project- Full Stack and Deployment on AWS CircleCi Github....

##Here We are using pre-configured front-End(angular.JS) and backend using NodeJS, ExpressJS, RDS Postgress as DB and for the continous deployment 
##AWS,Github,CircleCi.....

##This is a small application in which you can sign in and then you can add a picture just a simple idea but behind this simple idea goes a lot of backend ##technologies..








#### Deployment of Apllication Infrastructure

#### First We got the Technologies:

- AWS (Amazon Web Services) :

1- RDS (Relational Database):

- We create database based on our need , Capacity ,Scalability, Encryption , Backup and so on.
- Here is my LOCALHOST: database-1.coek0br4cgsf.us-east-1.rds.amazonaws.com
- Although this is public database.

2- S3 (Bucket)

- This is the store of our Frontend app also after marking it as static web site we got the link.

3- EB (Elasticbeanstalk)

- this is the store of our backend app although it has a link to check the routs and the data if we want.

-CircleCi (CI/CD framework)

- We use this framework to make a continous Integgeration

- Also we can offer Continuous Deployments

................................................................................................................................

### Second we get in this project this some of the used modules in the project:

##### 1-Node Package Manager v[14.15.0]

##### 2-Bestzip package v[2.2.1]

##### 3-Typescript v[3.9.10]

##### 4-Postgres pg v[8.7.1]

##### 5-AWS CLI v[2.7.16]

##### 6-EA CLI (Elasticbeanstalk) v[3.20.3]

##### 7-Sequelize v[5.21.4]

##### 8-express v[4.16.4]

##### 9-jsonwebtoken v[8.5.1]

##### 10-email-validator v[2.0.4]

##### 11-dotenv v[8.2.0]

##### 12-bcryptjs v[2.4.3]

##### 13-cors v[2.8.5]


................................................................................................................................

## Deployment of Pipeline Process

## Third  everyone has his own way to achieve and this is my own idea:

#### 1- Creating the Database in AWS RDS and store the parameter in .env file.

#### 2- Link the local application to Github Through pushing it.

#### 3- Link the CircleCLI Directly to Github throught signing in and link Github.

#### 4- After That Pass all the enviromet variable to the enviorment variable CircleCi and create the circlecli in the main directory of the full project.

#### 5- If the repo has been changed then Circlecli starts the CI then deployment to AWS.

#### 6- Through First Installing all the dependencies that's need to deploy the application in both front and back end seperately.

#### 6- After that in our application the deployment related to the manager to approve it.

#### 7- When the manager approve it Starting the deployment of front end in the S3 Bucket.

#### -8 IF the previous is successful then deployment of the backend will take place.

#### 7- IF there is any error in Pipeline in CircleCi the process stoped and also the deployment will not happen.

![16](https://user-images.githubusercontent.com/97471166/192146096-8ce98dee-ed44-49e9-beda-abf4e261f301.jpg)
<img width="810" alt="17" src="https://user-images.githubusercontent.com/97471166/192146108-b6d56a13-5935-4378-850e-b9dc7001e647.png">
![18](https://user-images.githubusercontent.com/97471166/192146116-d218baa5-dcbb-410b-abd1-494ba47f53bf.jpg)
![13](https://user-images.githubusercontent.com/97471166/192146329-04f036f7-7a0e-4c68-90c7-a77103a8e304.png)
![9](https://user-images.githubusercontent.com/97471166/192146339-4ac40808-fc51-44eb-8631-40ea22c4403d.png)
![6](https://user-images.githubusercontent.com/97471166/192146417-6d650292-12f3-473d-8c17-a362fdef438f.png)
![7](https://user-images.githubusercontent.com/97471166/192146418-d030dd5e-19ad-4aeb-b350-1c4cece25146.png)
![5](https://user-images.githubusercontent.com/97471166/192146456-d1b7737d-a15d-40e5-bcb4-93d984bac263.png)
![2](https://user-images.githubusercontent.com/97471166/192146457-a6fd751b-2b16-46da-bad5-c5bebac88b47.png)





### Mohamed Hassan Full Stack Project and continous deploymeny throught CirlceCi, AWS, Github
