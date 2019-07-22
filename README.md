https://raw.githubusercontent.com/gurulnd-git/aws-beanstalk-example-2/master/architecture.png

Flow
Source: Github
Continuous Integration: AWS CodeBuild - leveraged buildspec.yml to build the codebase
Continuous Deployment: AWS CodeDeploy - leveraged Amazon Elastic BeanStalk for deployment
REST Endpoints
Actuator endpoints are enabled under /actuator/*
Sample HelloController enabled under /hello
