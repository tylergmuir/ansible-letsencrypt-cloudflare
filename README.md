# ansible-letsencrypt-cloudflare

Ansible role to issue certificates from Let's Encrypt using Cloudflare public DNS

## Usage

Two variables are required to be past to use this role.
cloudflare_email: This is the email address for authenticating to cloudflare.
cloudflare_api_token: This is the api token for authenticating to cloudflare.

In the case that you are testing the role, you should use the staging URL for Let's Encrypt.
letsencrypt_url: [https://acme-staging-v02.api.letsencrypt.org/directory]
