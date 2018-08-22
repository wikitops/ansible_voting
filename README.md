# Ansible Voting App

The aim of this project is to deploy an example voting app on Kubernetes orchestrator.

## Getting Started

These instructions will get you a copy of the project up and running on your own Kubernetes cluster for development and testing purposes.

### Prerequisites

What things you need to run this Ansible playbook :

*   You must have a Kubernetes cluster up and running
*   Configure the host file based on your cluster

### Usage

Every deployment steps are managed by Ansible to be easily updated.

#### Deployment

To deploy the Voting application, you just have to run the Ansible playbook voting.yml with this command :

```
ansible-playbook voting.yml
```

If all run like it is expected, you should be able to access the voting and result web interfaces base on your Kubernetes cluster settings.

## Author

Member of Wikitops : https://www.wikitops.io/

## Licence

This project is licensed under the Apache License, Version 2.0. For the full text of the license, see the LICENSE file.
