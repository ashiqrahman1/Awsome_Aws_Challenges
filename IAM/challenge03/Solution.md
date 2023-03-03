# Lab Solution

Login to Your AWS Account

![Logo](https://i.ibb.co/x2x0ws4/Screenshot-from-2023-03-04-01-05-29.png)

Navigate To IAM Dashboard and Click Policies

![Logo](https://i.ibb.co/bJhhT8z/Screenshot-from-2023-03-04-01-09-23.png)

Now you have to create Custome Policies That Allow S3FullAccess and DynamoDbFullAccess

```
This Policies Allow Full Access to S3 and Dynamodb

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "VisualEditor0",
            "Effect": "Allow",
            "Action": [
                "s3:*",
                "dynamodb:*"
            ],
            "Resource": "*"
        }
    ]
}
```

![Logo](https://i.ibb.co/rmt2wt7/Screenshot-from-2023-03-04-01-16-31.png)

Click Next give "my_dev_access" as Policy Name

![Logo](https://i.ibb.co/qgmPpYL/Screenshot-from-2023-03-04-01-20-21.png)

Assign Policy To Developer Group

![Logo](https://i.ibb.co/4R1Fx0L/Screenshot-from-2023-03-04-01-21-39.png)

![Logo](https://i.ibb.co/zXZnrHr/Screenshot-from-2023-03-04-01-22-25.png)
