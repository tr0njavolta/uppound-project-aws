# UpPound Demo App Deployment

This repository is the code companion to the Upbound Docs Getting Started guide.
This project deploys an example pet adoption website on AWS EKS using Upbound.

## Prerequisites
- The Upbound CLI
- An Upbound Account
- An AWS account
- kubectl

## Get started

Clone this repository and run the authentication setup script:

```shell
./setup-aws-credentials
```

Build and run the project:

```shell
up project build && up project run
```

<<<<<<< HEAD
=======
Move the project to your Upbound account:

```shell
up project move ${yourUpboundaccount}/up-pound-project
```

>>>>>>> main
Deploy your resources:

```
kubectl apply -f examples/app/kcl/example.yaml
<<<<<<< HEAD

=======
>>>>>>> main
```
