
# LAB - Class 16

## Project : cloud-server

#### Author : Brenda Jow

### Problem Domain  

Deploy a simple Node.js server to EC2, using Elastic Beanstalk.

### Links and Resources

- [GitHub Actions ci/cd](https://github.com/rkgallaway/server-deployment-practice-d51/actions)
- [GUI Deploy](http://cloudserver-env.eba-egyawdjk.us-west-2.elasticbeanstalk.com/)
- [CLI Deploy](http://cloudserver-env.eba-egyawdjk.us-west-2.elasticbeanstalk.com/)

### Setup porcess

#### using GUI

1. zip the file you want to upload
2. follow the instruction prompted on screen to create an application with "Elastic Beanstalk" (GUI)

#### Using CLI

1. aws configure
  - set up region
3. eb init
4. eb create
5. eb deploy

#### Features / Routes

- Feature One: Details of feature
- GET : `/` - should see "hello from cloud server!"
- GET : `/hello` - should see "hello you"

#### UML

![uml](./simple%20UML.png)
