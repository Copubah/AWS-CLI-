# AWS CLI 
- AWS Command Line Interface is a tool for managing AWS services directly from the command line,it allows you to interact with AWS services using commands in your terminal,providing a convenient way to automate tasks,manage resources and control various AWS services


## Installation
- Python:ensure you have Python 3.6 or later versions on your system
- Pip:Python's package installer

## Linux
- pip install awscli

## macOS
- brew install aws cli

## Windows
- Use the MSI installer from the AWS CLI Installer


## Verify Installation
- aws --version 

## Configuration
- aws configure

## To list all s3 buckets
- aws s3 ls

## Deleting an s3 bucket
- aws s3 rb s3://bucket-name --force

## Creating EC2 intsances
- aws ec2 start-instance --instance-id i-4j3423ie i 32u89uf2