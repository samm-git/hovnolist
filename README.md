# Hovnolist

How to make user life miserable 

## Description

We are using [Terraform](https://www.terraform.io/), [Mikrotik provider](https://registry.terraform.io/providers/ddelnano/mikrotik/latest/docs), and [blacklist.salamek.cz](https://blacklist.salamek.cz) to inject data into the local Mikrotik DNS records

## How to use

1. Checkout
1. Run `terraform init`
1. Create a script to define `MIKROTIK_HOST/MIKROTIK_USER/MIKROTIK_PASSWORD` in it according to your device and add `terraform apply -auto-approve` to the end of it.

Enjoy, you just built censorship according to CZ laws.
