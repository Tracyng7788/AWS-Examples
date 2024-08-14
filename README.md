# AWS-Examples
A codebase of all the AWS examples used throughout AWS Study Courses

# Setup Common AWS Frameworks and Tools
# Install AWS CLI v2
pwd=$(pwd)
cd /tmp
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
cd $pwd

# Install CDK CLI
npm install -g aws-cdk
cdk --version

# Install YARN
npm install -g yarn
yarn --version

# Install AWS Amplify
npm install -g @aws-amplify/cli

# Install Taskfiles
npm install -g @go-task/cli

# Get Identity
export AWS_ACCESS_KEY_ID=
export AWS_SECRET_ACCESS_KEY=
export AWS_DEFAULT_REGION=
aws sts get-caller-identity

# Auto prompt featur
export AWS_CLI_AUTO_PROMPT=on-partial


# bash sripts
whereis bash 
#! /usr/bin/env bash (on your file)
# change permission to make it executable
chmod u+x s3/bash-scripts/* 
ls -la s3/bash-scripts
