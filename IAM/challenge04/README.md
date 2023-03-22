# Limiting Privileged User Access by Setting Permissions Boundaries in AWS IAM

In this hands-on lab scenario, you are a security engineer working for a new startup that's launching an online bookstore for rare and antique books. The founder, Kia, needs your help with setting up her system administrators with the proper access permissions. In order to provide access and ensure the proper security measures are in place, you will use AWS Identity & Access Management (IAM) to define a system administrators group and set permissions boundaries.

#### Lab Objective

Successfully complete this lab by achieving the following learning objectives:

    Part 01 (User/Group/Permission Setup)
    -----------------------------------------------------------------------
    - Login to AWS Console Create  `Sysadmin` group

    1) Create Three users and confiure console access
        - sysadmin1
        - sysadmin2
        - sysadmin3

    2) Add newly created users  to `Sysadmin` group

    3) Attach `AdministratorAccess` Policy to `Sysadmin` group

    4) Go to `Sysadmin` group click `sysadmin2` user and set permission boundary

        - attach `AmazonEC2FullAccess` Policy

    5) Go to `Sysadmin` group click `sysadmin3` user and set permission boundary

        - attach `AmazonS3FullAccess` Policy

    Part 02 (Verifying Limits on Privileged Users)
    -----------------------------------------------------------------------
    1) login to sysadmin3 and create a `S3` bucket

    2) Navigate to  EC2 service and try to create instance ( You should encounter a "not authorized to perform this operation" message)
