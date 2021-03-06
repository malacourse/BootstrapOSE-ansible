# OpenShift Enterprise Bootstrap Playbook
This playbook is used to prep a RHEL server, making it ready for the install of Red Hat OpenShift Enterprise Edition.

## REQUIREMENTS
You must be using Red Hat Enterprise Linux and Red Hat OpenShift Enterprise.
I recommend having Ansible configured and tested before using this playbook.

You must enter your host machines into the hosts file under [COMMON]. 

## Usage
```
ansible-playbook -i hosts openshift-prep.yml
```

## To Do for this playbook
- Create update hosts file
- Add repo logic so it won't remove and add repos every time the playbook is ran.
- Enhance the Subscription Manager section to search for OpenShift repos
- Deploy OpenShift master and nodes

## CONTACT
Matthew Ward
