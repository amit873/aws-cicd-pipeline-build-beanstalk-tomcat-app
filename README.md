# aws-cicd-pipeline-build-beanstalk-tomcat-app
aws cicd pipeline build beanstalk tomcat app

# Continuous Integration and Continuous Deployment using AWS CodePipeline Example

## Architecture
<img src="\src\main\webapp\AWS-CP-CC-CB-CD-LB-ASG-AWS-CP-CC-CB-Beanstalk.jpg" width="90%" />

## Flow
- Source: CodeCommit
- Continuous Integration: AWS CodeBuild - leveraged `buildspec.yml` to build the codebase
- Continuous Deployment: AWS CodeDeploy - leveraged Amazon Elastic BeanStalk for deployment

## Test App-
http://<IP>/

## Path for index.jsp -- 
\aws-cicd-pipeline-build-beanstalk-tomcat-app\src\main\webapp\index.jsp

## Examples --
http://tomacatcicddemo-env.eba-akmb7uqm.us-east-1.elasticbeanstalk.com/
