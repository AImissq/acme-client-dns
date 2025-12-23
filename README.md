# ACME DNS 01 challenge

This project is a proof of concept for obtaining SSL certificates using the ACME DNS-01 challenge with Let's Encrypt. It automates the process of validating domain ownership and generating SSL certificates by updating DNS records.

Dependencies 'dig' from 'bind9-dnsutils' (ubuntu) or 'bind9' complete package.

## Create a .env file:

Create a .env file in the root directory of the project with the following content:

EMAIL='your-email@example.com'  all without quotes
DOMAIN='yourdomain.com'

Tested and working on ubuntu 20.04
