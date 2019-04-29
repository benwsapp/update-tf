### Update local Terraform binary
Check to see if your local version of Terraform is compatible with the remote [state](https://www.terraform.io/docs/state "Terraform state") and update the version if it is incompatible.

## Requirements

This requires:

    * terraform
    * jq

Run from your Terraform directory:
```
$ curl -sL https://bensapp.com/scripts/update-tf | sh
```
