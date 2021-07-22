# Terraform
# Connecting to a AWS Instance in a private subnet using a Bastion host

## Introduction

This repo contains the required infrastructure to connect to an AWS Instance in a private subnet over a bastion host.

## Quick Start

To get started clone the repo:

```git clone https://github.com/ben-le/Terraform.git```

The repo requires you to have an AWS profile called: personal. It is possible to change the profile name in the variables.tf file.

The next step is to generate the key pair in the AWS console and safe the keys to your local system.

Replace a new keypair NAME to the instances.tf file.

Google how to create AWS key pair if needed.
