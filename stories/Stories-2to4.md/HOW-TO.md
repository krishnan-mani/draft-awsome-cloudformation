
* Perform the steps below as an account owner or IAM user that has administrative privileges

- For story-2:
  - You create an IAM group that has Administrative user privileges (using template in "create-admin-group")
  - You create a user that is a member of this IAM group (using template in "create-admin-user")
  - You then generate and download credentials (access key id + secret access key) for the user (by hand using the AWS Management Console)
  - You configure a profile for the use of these credentials with the AWS CLI on your workstation

```
$ aws configure --profile Jay@workshop

# Paste the 'AWS Access Key Id' and 'AWS Secret Access Key' from the downloaded credentials, 
# choose a 'Default region name' (such as "ap-south-1") and 'Default output format' (such as "json")
```

A script located in "iam-password-policy" must be applied to set the IAM password policy on the AWS account
```
$ cd evolution/iam-password-policy

```

The CloudFormation templates must be applied to create stacks in the following order:
 - create-admin-user

The stack "create-admin-user" needs a Parameter that is the name of the "created-admin-group" stack
