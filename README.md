# Ansible on Google Cloud using IAP

## Install

```shell
python3 -m venv venv
. venv/bin/activate
python3 -m pip install -r requirements.txt
```

## Usage

Edit `inventory.gcp.yml` and list your projects under `projects:`

```shell
ansible-playbook -v -i inventory.gcp.yml test.playbook.yml
```

## Documentation

- [Google Cloud Platform Guide - Ansible Documentation](https://docs.ansible.com/ansible/latest/scenario_guides/guide_gce.html)
- [Google.Cloud - Ansible Documentation](https://docs.ansible.com/ansible/latest/collections/google/cloud/index.html)

## Thanks

- [binx.io - How to tell Ansible to use GCP IAP tunneling](https://binx.io/2021/03/10/how-to-tell-ansible-to-use-gcp-iap-tunneling/)