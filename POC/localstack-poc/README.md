

## Deployment
```
serverless deploy --stage local
```

## Access Via API Gateway
```
curl 
```

## Accessing Localstack
```
aws --endpoint-url=http://localhost:4566 s3 ls
aws --endpoint-url=http://localhost:4566 s3 mb s3://test-bucket
```