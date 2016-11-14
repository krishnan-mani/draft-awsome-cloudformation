
* This workshop recommends that you begin with a new AWS account, but you can try this on an account that you have used earlier
* Perform the steps below as an account owner or IAM user that has administrative privileges
* It is advisable that you choose to use a single AWS region to create resources, such as Mumbai ("ap-south-1"). Some resources (CodeCommit repositories) can only be created in Virginia ("us-east-1") or Ohio ("us-east-2") regions

- Upload and create CloudFormation stacks using the templates in the "evolution" folder
- For story-1:
  - You create an IAM group that has Administrative user privileges
  - You create a user that is a member of this IAM group
  - You then generate and download credentials (access key id + secret access key) for the user
  - You configure a profile for the use of these credentials with the AWS CLI on your workstation

The CloudFormation templates must be applied to create stacks in the following order:
 - create-admin-group
 - create-admin-user

The stack "create-admin-user" needs a Parameter that is the name of the "created-admin-group" stack
