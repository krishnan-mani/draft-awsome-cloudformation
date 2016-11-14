
* This workshop recommends that you begin with a new AWS account, but you can try this on an account that you have used earlier
* Perform the steps below as an account owner or IAM user that has administrative privileges
* It is advisable that you choose to use a single AWS region to create (most of the) resources, such as Mumbai ("ap-south-1"). Some resources (CodeCommit repositories) will need to be created in Virginia ("us-east-1") or Ohio ("us-east-2") regions

- Upload and create CloudFormation stacks using the templates in the "evolution" folder
- For story-1:
  - You create an IAM group that has Administrative user privileges (using template in "create-admin-group")

The CloudFormation templates to be used:  
 - create-admin-group

The stack "create-admin-user" needs a Parameter that is the name of the "create-admin-group" stack
