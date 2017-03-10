# ansible-lab
This contains vagrant files to setup ansible practise lab.

## To start vagrant lab setup

you must get vagrant [installed](https://www.vagrantup.com/docs/installation/)
```
cd servera/
vagrant up

cd ../serverb/
vagrant up

cd ../workstation/
vagrant up

```
devops user has ability to do privilage escalation without prompting for password.
switch to student user, when you are logged in you will be in as vagrant user.

# ansible playbooks for aws

go inside ansible-playbook/

```
templates
handlers
files
site.yml
ec2.yml
db.yml
var.yml

```


