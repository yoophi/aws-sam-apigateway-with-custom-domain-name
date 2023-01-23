# AWS SAM / API Gateway with Custom Domain Name

## all in one template

```
/all-in-one
```

## certificate + api

```
/seperated
/seperated/certificate <-- ACM Certificate
/seperated/api         <-- Backend API
```

## 참고

- ACM 인증서는 반드시 `us-east-1`에 생성해야 함!
- CertificateArn 은 `arn:aws:acm:us-east-1:<aws-account-id>:certificate/<uniq-id>` 형식입니다.
