As an account owner,
I want to create an IAM group with privileges to administer the account,
To ensure administrative operations on the account are performed only by users in such group.

[create-admin-group]

As an account owner,
I want to create user(s) in the group with administrative privileges,
To ensure any further operations on the account are no longer performed using account owner credentials.

As an administrator,
I want to setup a secure IAM password policy,
To ensure any passwords used to access the AWS Management Console are not vulnerable.

As an administrator,
I want to generate the access credentials needed to act on the AWS account for the user,
To ensure authentication and authorization are in place to perform administrative actions.

[iam-password-policy]
[create-admin-user]

As an administrator, 
I want to create a version control repository (or repositories),
To use source control for automation and other resources, that will be used to maintain the environments.

As a contributor,
I want to obtain access to the version control repositories,
To collaborate via source artifacts published to the repository.

[collaborate-on-repositories]

As an administrator,
I want to setup Continuous Integration (using Jenkins)
To ensure changes are executed in a controlled fashion.

[jenkins-instance-profile]
[jenkins]

As collaborators,
We want to deliver changes in a controlled fashion to resources on the AWS account,
So we can multiply our efforts!
  - setup DNS domains, so DNS names can be setup.
  
