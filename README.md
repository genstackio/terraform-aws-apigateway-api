# AWS API Gateway v1 API Terraform module

Terraform module which creates API Gateway v1 resources on AWS.

## Usage

```hcl
module "api" {
  source     = "genstackio/apigateway-api/aws"

  name       = "my-api-name"
  lambda_arn = "arn:the-arn-of-the-lambda-here"
}
```
