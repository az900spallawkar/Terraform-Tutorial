# aws-instance-first-script

![](https://github.com/az900spallawkar/Terraform-Tutorial/workflows/terraform-tutorials-ci/badge.svg)

A Terraform module for creating AWS EC2 instance.

## Usage

```hcl
module "ec2_instance" {
  source     = "git::https://github.com/az900spallawkar/Terraform-Tutorial.git//aws-instance-first-script"

  region    = "us-west-2"
}
```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| region | AWS region | string | us-east-1 | yes |
