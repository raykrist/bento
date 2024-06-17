packer build -only=virtualbox-iso.vm -var-file=os_pkrvars/debian/debian-10-x86_64.pkrvars.hcl ./packer_templates
packer build -only=virtualbox-iso.vm -var-file=os_pkrvars/debian/debian-11-x86_64.pkrvars.hcl ./packer_templates
packer build -only=virtualbox-iso.vm -var-file=os_pkrvars/debian/debian-12-x86_64.pkrvars.hcl ./packer_templates
packer build -only=virtualbox-iso.vm -var-file=os_pkrvars/almalinux/almalinux-8-x86_64.pkrvars.hcl ./packer_templates
packer build -only=virtualbox-iso.vm -var-file=os_pkrvars/almalinux/almalinux-9-x86_64.pkrvars.hcl ./packer_templates
packer build -only=virtualbox-iso.vm -var-file=os_pkrvars/ubuntu/ubuntu-20.04-x86_64.pkrvars.hcl ./packer_templates
packer build -only=virtualbox-iso.vm -var-file=os_pkrvars/ubuntu/ubuntu-22.04-x86_64.pkrvars.hcl ./packer_templates
packer build -only=virtualbox-iso.vm -var-file=os_pkrvars/centos/centos-7-x86_64.pkrvars.hcl ./packer_templates
