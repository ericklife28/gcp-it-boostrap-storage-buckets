# gcp-it-boostrap-storage-buckets

This repository creates the cloud storage buckets that are used for storing the terraform state files.

## Setting values on terraform.tfvars

Go to theese .tfvars file and set these values with your own info

### terraform.tfvars


organization   = <your_organization_name>


### dev.tfvars

project_id     = <app_project_id>

### prod.tfvars

project_id     = <app_project_id>

### net.tfvars

project_id     = <app_project_id>

## Setting values on couldbuild.yaml

Go to the cloudbuild.yaml file and set the org right value in this section

env:
    - 'ORG=<your organization name>'


## Pushing the changes

1. Push the new changes to the repo

git add .
git commit -m "<your_message>"
git push

