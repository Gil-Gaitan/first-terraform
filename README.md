# Overview

This is a cloned repo to use for learning Terraform.

Lecture 1: Introduces a basic terraform nginx docker image. Runs some commands, look at it, then kill it. Helps learn basic commands and see how to build the image.

Lecture 2: Lock and state files, also docker providers to share resources

Lecture 3: Variables are covered

Lecture 4: More Variables, like ports. Setting defaults or not. file for all variables in one place

Lecture 5: AWS setup. New aws provider + version, define region. Take AWS instance and webserver
    AMI and instance block, get AMIU by searching
    Datablock - T2 micro - in variables
    new variable output, output AWS instance
    Public ip aws_instance.webserver.ip_instance / type.name.attribute
    Setup AWS Account:
        launch environment. access to account, un, password, keys
        grab environment keys enter in termainal in folder
            AWS_ACCESS_KEY_ID=
            AWS_SECRECT_ACCESS_KEY=
        Now terraform can run this w AWS instance, terraform plan
        publicIP shows as output.
        Apply - create the instance
        Login to AWS console, with un and password, look st EC2 instance with same IP address.
        destroy it. refresh and see the instance shutting sown on console and terminal.
  
Lecture 6: Datablocks

Lecture 7:

Lecture 8:

Lecture 9:

[blog post credit for turtorial](https://tekanaid.com/posts/terraform-for-beginners-course-and-training)
