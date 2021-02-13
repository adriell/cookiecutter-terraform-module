# Módulo Terraform - {{ cookiecutter.terraform_provider }} - {{ cookiecutter.terraform_module }}

Módulo do Terraform para provisionamento de....


## Uso

```hcl
module "{{ cookiecutter.module_slug }}" {
  source = "git::ssh://git@example.com/terraform-modules/{{ cookiecutter.module_slug }}.git?ref=v0.1.0"

  name          = "TF - exemplo"
  tags {
    Name = "tf-testes"
  }
}
```

## Recursos provisionados


## Customizações


## Licença

Apache Licensed. See LICENSE for full details.
