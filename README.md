# AWS Direct Links To FAQ and best practices

I am updating this page on the go while learning AWS configuration and different services to keep the best resources and links I found on AWS docs, youtube and blogs.

##EC2
> - Default AWS account limits allow you to launch up to 20 Amazon EC2 instances.

##OpsWorks

> - AWS OpsWorks is a flexible **`configuration`** management solution
> - By default, you can create up to **`40`** Stacks, and each stack can hold up to **`40`** layers, **`40`** instances, and **`40`** apps.


[[Video] What is OpsWorks](Introduction to AWS OpsWorks)

[[Lab] OpsWorks FREE practice lab](https://qwiklabs.com/focuses/preview/2361?locale=en)

[[Blog] Deploying Symfony2 to AWS using OpsWorks](http://blog.codebender.cc/2016/01/19/symfony2-at-amazon-opsworks-part-1/)

[OpsWorks FAQ](https://aws.amazon.com/opsworks/faqs/)

[Deployment Best Practice](https://docs.aws.amazon.com/opsworks/latest/userguide/best-deploy.html)


## Comparison between OpsWorks, Elastic Beanstalk and CloudFormation

| OpsWorks | Elastic Beanstalk | CloudFormation |
| --- | --- | --- |
| Configuration management | Application Management | Configuration Management |
| Chef recipe and cookbooks for management| Yaml and application code | JSON based notation for management|
| AWS OpsWorks supports a narrower range of application-oriented AWS resource types including Amazon EC2 instances, Amazon EBS volumes, Elastic IPs, and Amazon CloudWatch metrics | Limited resources, almost same as OpsWorks |  Provision and manage almost any AWS resource |
