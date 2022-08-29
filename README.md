<h1>This is a basic readme for the project</h1>

<h2>This is the circleci project pipeline passed status.</h2>

[![CircleCI](https://circleci.com/gh/circleci/udagram-app-final.svg?style=svg)](https://app.circleci.com/pipelines/github/SO-HYBE/udagram-app-final/1/workflows/80029656-6db4-4907-9e8b-2a0ab735802f)

![circleci](https://user-images.githubusercontent.com/44274982/187129284-8b700e33-3cf2-4018-b259-23ae2a27bd00.PNG)

```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::projectbuck123/*"
        }
    ]
}

```
<h2>This project is a deployment process project for udacity web development advanced track. It utilizes a lot of AWS services, circleci, and many other modules. It uses the AWS S3 service which is used as a deployment platform for the frontend of the project. It also uses AWS RDS as the server-side of the project which mainly saves the data of the users. In addition, the project uses AWS Elastic Beanstalk and EC2 which deploys the api-side of the project and connects to the S3 for the project to run. Finally, it uses AWS CLI and EB CLI to make the deployment automated using CircleCi.</h2>

<h3>AWS CLI</h3>
<a href="https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html" target="_blank">AWS CLI DOCS</a>

<h3>Configuring AWS CLI</h3>

```
aws configure
```
<a href="https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html" target="_blank">AWS CLI DOCS</a>



