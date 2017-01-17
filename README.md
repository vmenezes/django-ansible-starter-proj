django-ansible-starter-proj
===========================

This is a simple boilerplate for a Django/Celery project running on Ubuntu with NGINX and local Postgres/Redis. It uses Vagrant/Ansible for provisioning.

## Versions

- Ubuntu 16.04 LTS 64bits
- Python 3.5 (default on Ubuntu 16)
- Django 1.10
- Celery 4.0
- Postgres 9.5
- Redis ???
- Ansible 2.1
- Vagrant 1.9.1

## Environments

This project ready for 3 environments:

- Local
 - Created by Vagrant
 - Provisioned by Ansible
 - Used for development

- Staging
 - This is expected to be an already up "clean" instance of Ubuntu 16(AWS EC2, Ditatalocean, etc).
 - Provisioned by Ansible
 - As the name suggests, used for QA

- Production
 - This is expected to be an already up "clean" instance of Ubuntu 16(AWS EC2, Ditatalocean, etc).
 - Provisioned by Ansible
 - As the name suggests, this is the production server

## Getting started

### Local requirements

To Use this boilerplate one must have at least these applications bellow installed on the machine.

- Virtualbox 5.0.20
- Ansible 2.1.7
- Vagrant 1.9.1
- SSH client

PS: other versions may work, just try to stick to the release version(for example, do not expect it to work with Ansible 1.8 but it most likely works with any => 2.0).

### Main directories

- `/var/www/my_proj/`
- `/var/run/my_proj/`
- `/home/ubuntu/venvs/`
- `/etc/nginx/sites-available/`
- `/etc/tmpfiles.d/`
- `/vagrant/`

