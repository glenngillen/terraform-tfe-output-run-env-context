# Output Terraform Cloud ENV 

A Terraform module to output the value of environment variables available/set in the context of a run. Helpful for 
debugging and/or working out what values are dynamically set by Terraform Cloud.

## Usage

``` 
module "debug-env" {
  source  = "glenngillen/output-run-env-context/tfe"
}
```