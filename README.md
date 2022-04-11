OpenShift Provisioning and Configuration on VMware
===================================================

This repository contains Ansible playbooks and roles to automate a UPI OpenShift 4 install on VMWare

This blog post covers the provisioing process in detail: [Provision Red Hat CoreOS (RHCOS) Machines With Custom V3 Ignition Files](https://www.openshift.com/blog/provision-red-hat-coreos-rhcos-machines-with-custom-v3-ignition-files)


Requirements
------------

The following collections are required:
- community.kubernetes
- community.vmware

The following python packages are required:
- jmespath
- openshift
- kubernetes
- pyvmomi

The following packages are required:
- ansible
- jq
- httpd

The following binaries are required:
- openshift-install
- oc

Role Variables
--------------

The role variables are all set in a single file inside the vars directory.
