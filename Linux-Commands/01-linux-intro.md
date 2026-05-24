## Linux ##
## Linux Defination:


## Server:

## Protocol

## Domain

## IP Address

## Ports


## Absolute And Relative Path


## Linux Server Creation
path:
EC2 -> Instances --> Launch Instances --> name of the Instance <eg:-linux> --> select free Amazon linux 2023 --> Instance type (t2.micro , t3.micro) --> Select Key-pair --> Select Security Group --> Launch Instance == this will create the server

To connect to the Linux Server
```
ssh -i <private-key name> <linux-user>@ip-address
```
eg:- ssh -i aws-linux-key.pem ec2-user@ip-address

