# Github Pages Hosting

## Overview

https://gohugo.io/hosting-and-deployment/hosting-on-github/

## How to Deploy

Run the `deploy.sh` script in this repository

# GCP Static Site Hosting

## Overview

!! Went with Github Pages as GCP static site hosting doesn't provide SSL out of the box !!
https://cloud.google.com/storage/docs/hosting-static-website

## How to Deploy

Install [Hugo CLI](https://github.com/gohugoio/hugo/releases)
Set the [environment variable correctly](https://cloud.google.com/docs/authentication/production#obtaining_and_providing_service_account_credentials_manually)
Run `hugo deploy`

# Remaining TODOs

- Add photo
- Proof read content
- New tag line
- Confirm SSL once Github Pages generates the certificate
- Implement form to actually send email
- Setup analytics
