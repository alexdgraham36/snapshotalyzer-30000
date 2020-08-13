# snapshotalyzer-30000

Demo project to manage AWS EC2 instance snapshots

# About

This project is a demo working through the Cloud Guru training, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the Configuration file created by the AWS CLI e.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <--project=PROJECT>`

*command* is list, stop, or start
*project* is optional and uses the AWS Project tag
