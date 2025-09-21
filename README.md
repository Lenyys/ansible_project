
# Nginx Server Provisioning with Ansible, Vagrant, and VirtualBox

This project provisions and configures an **Nginx web server** using **Ansible** inside a **VirtualBox VM** managed by **Vagrant**.  

## Prerequisites
 - vagrant
 - Virtualbox

## Getting Started
 - Clone the repository:

```bash
git clone https://github.com/Lenyys/ansible_project.git
cd ansible_project

- Start and provision the virtual machine:

```bash
vagrant up

```
- Connect to the VM

```bash
vagrant ssh

```

3. Run Ansible playbook:

```bash
ansible-playbook -i /vagrant/inventory /vagrant/playbooks/site.yml

```


## now you can run http://localhost:8080 in your browser