# Ansible Role: php-webtatic

[![Build Status](https://travis-ci.org/alamsyahho/ansible-php-webtatic.svg?branch=master)](https://travis-ci.org/alamsyahho/ansible-php-webtatic)

Install and configure php 5.6, php 7.0 or php 7.1 based on the package from webtatic repositories. Currently this role is only supported RedHat/CentOS 6 and 7

## Requirements

CentOS 6/7 Minimal Installation

## Example Playbook

`install-php-webtatic.yml`

    - hosts: all
      vars:
        php_version: php56
        
      roles:
        - php-webtatic

Running playbook on specific hosts:

    ansible-playbook -i host1.example.com,host2.example.com install-php-webtatic.yml

## License

MIT
