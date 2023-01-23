# api

## install, update and destroy

```
sam build
sam deploy --guided
sam deploy # for update
sam delete # for delete stack
```

## outputs

```
-----------------------------------------------------------------------------------------------------
Outputs
-----------------------------------------------------------------------------------------------------
Key                 HelloWorldApiURL
Description         API Gateway endpoint URL for Prod stage for Hello World function
Value               https://test.example.com/hello/

Key                 HelloWorldFunctionIamRole
Description         Implicit IAM Role created for Hello World function
Value               arn:aws:iam::<acount-id>:role/<role-name>

Key                 HelloWorldApiGatewayURL
Description         API Gateway endpoint URL for Prod stage for Hello World function
Value               https://<uniq-id>.execute-api.<aws-region>.amazonaws.com/Prod/hello/

Key                 HelloWorldFunction
Description         Hello World Lambda Function ARN
Value               arn:aws:lambda:...
-----------------------------------------------------------------------------------------------------
```
