
- This workshop assumes and recommends that you begin with a new AWS account
- Upload and create CloudFormation stacks using the templates in the "evolution" folder
- For story-1, 

- You create an IAM group that has Administrative user privileges
- You create a user that is a member of this IAM group
- You then generate and download credentials (access key id + secret access key) for the user
- You configure a profile for the use of these credentials with the AWS CLI on your workstation

The CloudFormation templates must be applied to create stacks in the following order:
 - create-admin-group
 - create-admin-user

- You also need to run the following scripts
