# snapshotalyzer-30000

Demo project to manage AWS EC2 instance Snapshots

## About

This project is a demo, and uses boto3 to manage EC2 snapshots

## Configuring

shotty users the configuration file create by the AWS cli. e.g.

'aws configure --profile shotty'

## Running

'pipenv run "python shotty/shotty.py" <command> <--project=Project>"'

*command* is list, start or stop
*project* is optional

