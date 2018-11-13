# redbot

This is a vagrant box for developing and running Red-DiscordBot.

This Vagrant environment has been created by adapting instructions from [JetBrains][1]

## Files
* requirements.txt: This is the python modules needed by the redbot virtualenv
* setup.yml: The Ansible file used by Vagrant's provisioning command
* Vagrantfile: Creates a VM using bento/ubuntu-18.04 and provisions it with Ansible

[1]: https://blog.jetbrains.com/pycharm/2017/12/developing-in-a-vm-with-vagrant-and-ansible/ "Developing in a VM with Vagrant and Ansible"
