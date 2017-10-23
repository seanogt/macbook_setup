Go to the following site and follow the instructions: [Geerlinggy's mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook)

The config.yml file contains all the applications installed on my macbook pro. 

Create the following symlinks:

`ln -s ../macbook_setup/config.yml config.yml`
`ln -s ../macbook_setup/custom-ansible-tasks/ custom-ansible-tasks`

Run ansible-playbook:

`main.yml -i inventory -K from the mac-dev-playbook directory`

The macdefaults.sh script can be run separately as a standalone bash script (for now!).

The gitdefaults.sh script can be run separately as a standalone bash script (for now!).


