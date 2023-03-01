# Introduction to AWS Identity and Access Management (IAM)

IAM

# Description

AWS Identity and Access Management (IAM) is a service that allows AWS customers to manage user access and permissions for their accounts, as well as available APIs/services within AWS. IAM can manage users and security credentials (such as API access keys), and allow users to access AWS resources.

In this lab, we will walk through the foundations of IAM. We'll focus on user and group management, as well as how to assign access to specific resources using IAM-managed policies. We'll learn how to find the login URL, where AWS users can log in to their account, and explore this from a real-world use case perspective.\*

## Lab Objective

#### Successfully complete this lab by achieving the following learning objectives:

- Login to Your AWS Account and Create These Users and Group

  - username name should be

    - john
    - bob
    - alice

  - group name should be

    - S3-Support
    - EC2-Support
    - EC2-Admin

  - Attach users to Respective Groups

    - john should be in S3-Support
    - bob should be in EC2-Support
    - alice should be in EC2-Admin

  - Attach Policy to Groups
    - ec2-admin policy to EC2-Admin Group
    - ec2-support Policy to EC2-Support
    - s3-support Policy to S3-Support

#### Attach Custome Policies to the Groups [Dont Worry if you don't know how to create your own policies All the Policies Required For the Lab Attached in The Respository]

---

#### Happy Hacking
