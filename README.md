# Ansible AWS
Creating AWS VPC, 2x EC2 instances and RDS via Ansible

A complete Ansible project to create one NAT instance with a public network, while the other instance is also RDS in a private network.

## AWS VPC

In this role we have fully manage of AWS network, from creating own VPC to setup Subnets, Security groups and other stuffs.

## AWS NAT and APP instance

In this project we have two instances one is NAT with public access, and other is APP with private access across Security group from NAT instance.

## AWS RDS

For RDS instance we use Aurora AWS with MySQL 5.7.
First we create cluster, and then create Database.


