# ansible-role-aws-ecr-proxy

# Overview

Uses a simple nginx based push/pull container as an ECR proxy. The container is [aws-ecr-proxy](https://github.com/bdellegrazie/docker-aws-ecr-proxy)

## Why another fork?

I wanted to separate the building of the container with a role that could be deployed to Ansible Galaxy as well as update both the proxy and the role

## Role Variables:

See [defaults/main.yaml](https://github.com/bdellegrazie/ansible-role-aws-ecr-proxy/tree/master/defaults/main.yml) and modify
according to your needs. You may also need the environment variables as per container github repository

## Note on SSL/TLS

If you want to enable SSL/TLS please supply appropriate pem files as per the docs.

## Authors + Copyright

[Original: Lotto24/eSailors](https://github.com/Lotto24/aws-ecr-http-proxy)

[This Fork: bdellegrazie](https://github.com/bdellegrazie/ansible-role-aws-ecr-proxy)
