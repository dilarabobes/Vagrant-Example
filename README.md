# Vagrant Example

This project provides a simple Flask Application running on VMware VM that is managed by Vagrant.

## Technologies

This project is created with:
- Flask
- Vagrant
- VMware

## Set Up

Since VirtualBox is the default provider for Vagrant, it is changed to VMware with this command:

```bash
export VAGRANT_DEFAULT_PROVIDER=vmware_desktop
```

## Usage

To create VM with Vagrant, run this command:

    $ vagrant up

To see the running application, navigate to http://localhost:5001/ after all commands are executed.
