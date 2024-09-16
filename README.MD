### VPC

This module is going to create
* VPC
* Internet gateway
* 2 Public subnets
* 2 Private subnets
* 2 Database subnets

###
* cidr_block(required)- User has to provide cidr block
* enable_dns_hostnames(optional) - User can provide enable_dns_hostnames, ***default is true***

* enable_dns_support(optional) - User can provide enable_dns_support, ***default is true***

* common_tags - User can provide tags for all resources, ***default is empty***

* vpc_tags(optional) - User can provide vpc tags for vpc resources, ***default is empty***

* igw_tags(optional) - User can provide igw tags for internet gateway resources, ***default is empty***

* public_subnet_cidr(required) - User must provide a list of 2 public subnet cidr

* public_subnet_names(required) - User must provide a list of 2 public subnet names

* private_subnet_cidr(required) - User must provide a list of 2 private subnet cidr

* private_subnet_names(required) - User must provide a list of 2 private subnet names

* database_subnet_cidr(required) - User must provide a list of 2 database subnet cidr

* database_subnet_names(required) - User must provide a list of 2 database subnet names