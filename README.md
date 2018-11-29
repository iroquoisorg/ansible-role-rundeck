# rundeck

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-rundeck.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for rundeck

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.rundeck`

# Default settings

```

rundeck_version: 2.7.3
rundeck_host: localhost
rundeck_port: 80
rundeck_ssl_port: 443

rundeck_internal_port: 4440
rundeck_internal_ssl_port: 4443

rundeck_expire_days: 20
rundeck_api_key: ""
rundeck_expire_projects: "[]" # string with python array

```
