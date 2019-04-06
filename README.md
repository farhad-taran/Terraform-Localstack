# Terraform-Localstack sample

this repo contains a docker-compose file which brings up a localstack container with sqs,sns,s3 services and the terraform template can modify these services for s3 notifications into sqs.

# Bring up local stack

```
docker-compose -d
```

# Download Terraform AWS provider

```
terraform init
```

# See the deployment plan and accept it by typing yes

``` 
terraform plan
```

# Apply the plan and deploy the infrastructure

```
terraform apply
```
