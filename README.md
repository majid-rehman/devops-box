# DevOps box
* A vagrant project with an ubuntu box with the tools needed to do DevOps

## Set up the devops-box

**1. Install Vagrant and VirtualBox:**

- [Download Vagrant](https://www.vagrantup.com/downloads.html)
- [Download VirtualBox](https://www.virtualbox.org/wiki/Downloads)

**2. Clone the devops-box:**


```
git clone https://github.com/majidkhan138/devops-box.git && cd devops-box
```

**3. Start Vagrant:**

```
vagrant up
```


**4. SSH into the sandbox:**

To start using the devops-box:

```
vagrant ssh
```

_NOTE: To exit out of the sandbox, use `CTRL`+`D`.
Use `vagrant destroy` then `vagrant up` to erase and restart the sandbox._

---

# tools included
* Terraform
* AWS CLI
* Ansible
