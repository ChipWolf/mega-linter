<!-- markdownlint-disable MD003 MD020 MD033 MD041 -->
<!-- @generated by .automation/build.py, please do not update manually -->
<!-- Instead, update descriptor file at https://github.com/nvuillam/mega-linter/tree/master/megalinter/descriptors/terraform.yml -->
# TERRAFORM

## Linters

| Linter                                      | Configuration key                                     |
|---------------------------------------------|-------------------------------------------------------|
| [tflint](terraform_tflint.md)               | [TERRAFORM_TFLINT](terraform_tflint.md)               |
| [terrascan](terraform_terrascan.md)         | [TERRAFORM_TERRASCAN](terraform_terrascan.md)         |
| [terragrunt](terraform_terragrunt.md)       | [TERRAFORM_TERRAGRUNT](terraform_terragrunt.md)       |
| [terraform-fmt](terraform_terraform_fmt.md) | [TERRAFORM_TERRAFORM_FMT](terraform_terraform_fmt.md) |
| [checkov](terraform_checkov.md)             | [TERRAFORM_CHECKOV](terraform_checkov.md)             |

## Linted files

- File extensions:
  - `.tf`

## Configuration in Mega-Linter

| Variable                       | Description                   | Default value |
|--------------------------------|-------------------------------|---------------|
| TERRAFORM_FILTER_REGEX_INCLUDE | Custom regex including filter |               |
| TERRAFORM_FILTER_REGEX_EXCLUDE | Custom regex excluding filter |               |

