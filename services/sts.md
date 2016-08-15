| Action | Description | Resource | Condition |
| --- | --- | --- | --- |
| [sts:AssumeRole](http://docs.aws.amazon.com/STS/latest/APIReference/API_AssumeRole.html) | Returns a set of temporary security credentials (consisting of an access key ID, a secret access key, and a security token) that you can use to access AWS resources that you might not normally have access to. | arn:aws:iam::$account-id:role/$role-name | - |
| [sts:AssumeRoleWithSAML](http://docs.aws.amazon.com/STS/latest/APIReference/API_AssumeRoleWithSAML.html) | Returns a set of temporary security credentials for users who have been authenticated via a SAML authentication response. | ??? | - |
| [sts:AssumeRoleWithWebIdentity](http://docs.aws.amazon.com/STS/latest/APIReference/API_AssumeRoleWithWebIdentity.html) | Returns a set of temporary security credentials for users who have been authenticated in a mobile or web application with a web identity provider, such as Amazon Cognito, Login with Amazon, Facebook, Google, or any OpenID Connect-compatible identity provider. | ??? | - |
| [sts:DecodeAuthorizationMessage](http://docs.aws.amazon.com/STS/latest/APIReference/API_DecodeAuthorizationMessage.html) | Decodes additional information about the authorization status of a request from an encoded message returned in response to an AWS request. | ??? | - |
| [sts:GetFederationToken](http://docs.aws.amazon.com/STS/latest/APIReference/API_GetFederationToken.html) | Returns a set of temporary security credentials (consisting of an access key ID, a secret access key, and a security token) for a federated user. | arn:aws:sts::$account-id:federated-user/$user-name | - |
| [sts:GetSessionToken](http://docs.aws.amazon.com/STS/latest/APIReference/API_GetSessionToken.html) | Returns a set of temporary credentials for an AWS account or IAM user. | arn:aws:iam::$account-id:mfa/$virtual-device-name | - |