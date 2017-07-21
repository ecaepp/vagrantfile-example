# vagrantfile-example

This project is built to be a simple and reusable Vagrant setup that allows for easy to configure multibox setup using a yaml config file to build the proviosion the vagrant boxes.

This project is ideal for someone looking to start using Vagrant or wants to simplify their current vagrant setup.

## Getting Started

It is recommended that you go though the documentation for Vagrant if you have not used the
program before just familiarize yourself with it a bit.\
[Vagrant Docs](https://www.vagrantup.com/docs/index.html)

```angular2html
DISCLAIMER!!!! Vagrant boxes are built insecurely and should only be used in dev/testing environments and never in production.
```
### Prerequisites

A current and working installation of Vagrant is required for this project. Downloads for vagrant can be found at [Vagrant Downloads](https://www.vagrantup.com/downloads.html)

### Installing

Installation is as simple as just cloning the repo to your dev/test folder.

If you do not have git or are restricted from from downloading the  simply creating the files locally and coping the contents to them will work.

### Configuration
The Vagrantfile is designed to import the `config.ymal` file and iterate though it to build the boxes.

The `config.ymal` file has commented out examples that can be modified and used to build the boxes by changing
the values in the file.

```angular2html
At this time only one type of provisioner can be used at a time, and the Vagrantfile comes defaulted to Ansible and will
need to be modified to use a different provisioner such as shell or puppet.
```

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE.md](LICENSE) file for details

