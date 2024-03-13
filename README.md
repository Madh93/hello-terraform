# Hello Terraform

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

Basic "Hello World" example in Terraform provisioning a local file.

## Requirements

- [Terraform](https://developer.hashicorp.com/terraform/install)

## Usage

Clone the repository and initialize the project:

```shell
terraform init
```

Review the Terraform execution plan:

```shell
terraform plan
```

Apply the Terraform configuration to provision resources:

```shell
terraform apply
```

After Terraform has finished applying the configuration, you should see the output indicating the resources that were created. In this case, a `hello.txt` file.

To clean up and destroy the resources created by Terraform, run:

```shell
terraform destroy
```

## Useful Links

- [Terraform](https://www.terraform.io/)
- [Terraform Docs](https://developer.hashicorp.com/terraform/docs)
- [Terraform Tutorials](https://developer.hashicorp.com/terraform/tutorials)

## License

This project is licensed under the [MIT license](LICENSE).
