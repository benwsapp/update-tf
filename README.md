### Update local Terraform binary
Check to see if your local version of Terraform is compatible with the remote [state](https://www.terraform.io/docs/state "Terraform state") and update the version if it is incompatible.

Run from your Terraform directory:
```
$ curl -sL https://raw.githubusercontent.com/benwsapp/update-tf/master/sync | sh
```