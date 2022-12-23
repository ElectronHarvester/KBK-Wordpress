# KBK-Wordpress
A guide to setting up Kertz Beekeeping's Wordpress site.


## Getting Started 
### Creating Droplet
1. Sign into [Digital Ocean](https://cloud.digitalocean.com/) 
2. Create a new droplet:  
- Select "Marketplace" > Wordpress 5.8 on Ubuntu 20.04
- No DB cluster
- Shared CPU
- Regular ssd
- 1GB memory, 1CPU, 25GB SSD, 1000 GB transfer.
- Hosted in NY-1
- No block storage
- default VPC
- Enable Backups
Create

- Assign appropriate reserved IP to the new droplet.

- Add subdomain np.[websiteurl] to DNS records pointing to reserved IP.


### Setting up Wordpress
- ssh root@[reserved ip address]
- run through the wp install
- add support for ssh

Login to https://np.kertzbeekeeping.com/wp-admin
- Update wordpress and all plugins
- install "spacious" theme
- Follow guide to install ThemeGrill plugin and import "Spacious Farm" Starter


- remove all excess plugins and themes


### Still working on. 
- Getting letsencrpyt set up. 
+ currently this is failing, investigate how to use a domain to fix this. 

- Getting a domain routed. 
- Getting started from a snapshot. 
