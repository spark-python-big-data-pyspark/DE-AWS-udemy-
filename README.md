# DE-AWS-udemy-

0. [Configure AWS](#schema0)
1. [Config](#schema1)
2. [Cloud9](#schema2)
3. [Docker and AWS CLI](#schema3)
4. [Cloud9 and EC2](#schema4)
2. [Ref](#schemaref)

<hr>
<a name='schema0'></a>

## 0. Configure AWS and jupyter lab

```bash
aws configure
```

```bash
aws configure set aws_session_token ""
```
```bash
jupyter lab
```


<hr>
<a name='schema1'></a>

## 1. Config

1. Install Virtual Env
2. Create Env
3. Install Jupyter Lab
4. Install Boto3
5. Install Cloud9


<hr>
<a name='schema2'></a>

## 2. Cloud9

AWS Cloud9 is a cloud integrated development environment (IDE) that provides a set of tools for writing, running, and debugging code. It is designed especially for developers working on cloud projects, enabling real-time collaboration and providing access to AWS cloud resources directly from the IDE.

![Cloud](./img/cloud9.png)


<hr>
<a name='schema3'></a>

## 3. Docker and AWS CLI

![Docker - AWS](./img/docker-aws.png)

<hr>
<a name='schema4'></a>

## 4. Cloud9 and EC2

![cloud9 - ec2](./img/cloud9-ec2.png.png)

- Configure Http

```bash
sudo systemctl status httpd
```
```bash
sudo systemctl start httpd
```

```bash
telnet localhost 80
```
- Configure Security group EC2
  - edit inbound rules 
    - http, my ip






<hr>
<a name='schemaref'></a>

REF: https://www.udemy.com/course/data-engineering-using-aws-analytics-services/