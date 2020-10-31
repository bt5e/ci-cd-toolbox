CI/CD Toolbox
=============

CI/CD toolbox based on CentOS. Available on [Vagrant Cloud](https://app.vagrantup.com/btse/boxes/ci-cd-toolbox).

## Components

| Component           | Version |
| ------------------- | ------- |
| [CentOS             ](https://app.vagrantup.com/bento/boxes/centos-7)           | 7       |
| [Docker CE          ](https://github.com/bt5e/ansible-role-docker-ce)           | 19.3.13 |
| [Dcoker Compose     ](https://github.com/bt5e/ansible-role-docker-compose)      | 1.27.4  |
| [helm               ](https://github.com/bt5e/ansible-role-k8s-helm)            | 3.4.0   |
| [HashiCorp Terraform](https://github.com/bt5e/ansible-role-hashicorp-terraform) | 0.13.5  |
|  kubectl                                                                        | latest  |
|  Google Cloud SDK                                                               | latest  |

## Build

    ansible-playbook playbook.yml
