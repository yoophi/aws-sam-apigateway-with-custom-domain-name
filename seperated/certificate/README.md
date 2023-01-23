# certificate

## install, update and destroy

```
sam build
sam deploy --guided --region us-east-1
sam deploy # for update
sam delete # for delete stack
```

## outputs

```
-----------------------------------------------------------------------------------------------------
Outputs                                                                                                                                      
-----------------------------------------------------------------------------------------------------
Key                 Certificate                                                                                                              
Description         CertificateArn                                                                                                           
Value               arn:aws:acm:us-east-1:12345678:certificate/12345678-abcd-abcd-abcd-123456781234                                      
-----------------------------------------------------------------------------------------------------
```
