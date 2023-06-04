# provisioning-playbook
Playbooks containing common provisioning tasks

## Prerequisites
Some of the playbooks use modules from the following collections.
  - [community.general](https://galaxy.ansible.com/community/general)

To install, run: `ansible-galaxy collection install community.general`.

## Usage

1. Add target hosts into `/inventory`.
2. Run the playbook.
    ```bash
    ansible-playbook ./ubuntu.yaml -i ./inventory
    ```