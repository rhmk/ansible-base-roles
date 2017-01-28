# ansible-roles

###
# the follwoing roles are defined

collect-ssh-hostkeys: 
  fetches hostkeys from managed host and update all others

workstation-setup:
  - installs all packages useful for workstations
  - configures user from variables with default passwords / collect passwords

redhat-internal:
  configures redhat internale software stacks such as
  - printers
  - templates for libreoffice
  - VPN
  - bluejeans
  
mail-setup:
  - configures postfix for use with 1&1
  - configures Email aliases

ssh-setup:

multi-media-setup:

dev-android:

dev-kernel:

dev-basic:

dev-tools:

