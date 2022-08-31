# API Gateway Quota Usage



## Deployment

- Configure AWS IAM credentials
```
sls config credentials --key AKIAIOSFODNN7EXAMPLE --secret wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
```
- Create a SLS Project
```
sls create --template aws-python3 --name api-key-quota-usage --path api-key-quota-usage
```
```
sls deploy
```
- To completely remove the deployed resources
```
sls remove
```


## Reference

- [Serverless Framework API gateway quota usage](https://www.serverless.com/framework/docs/providers/aws/events/apigateway#setting-api-keys-for-your-rest-api)

