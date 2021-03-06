# TerraOak - Finding Design Gaps Daily
![TerraOak](oak9-logo.png)

TerraOak is Oak9's vulnerable IAC code repo.   This repo will be used for learning and training purposes on how to implement a cloud security posture. 

## Table of Contents

* [Introduction](#introduction)
* [Blast Off](#getting-started)


## Introduction 

Before you proceed, WARNING:
> :warning: TerraOak is a test repo for creating Vulnerable resources, please use at your own discrention, Oak9 is not responsible for any damages. **DO NOT deploy TerraGoat in a production environment or any AWS accounts that contain sensitive information.**

TerraOak is a public repo available to the general audience to showcase the Oak9 cli in action.  It can be used to test our dynamic blueprint engine to show validate terraform code for design gap security issues.

## Scenario

Lets Build a petstore API using the below resources. 

* elb
* route53 
* cloudfront
* dyanmodb
* s3 
* lambda 


## Getting started

Downloading the TerraOak Cli and the instructions on how to run it can be found here, https://docs.oak9.io/oak9/fundamentals/integrations/cli-integration

## Terraform Code 

The code in this repo should not be run inside of your company's aws accounts but rather in a playground account.   

## Running it inside of a docker container


## Requirements

* Terraform 0.12
* aws cli
* local jenkins instance for jenkins integration testing 