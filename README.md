# base-ruby-box-experiment
A set of ansible scripts to hook up a Vagrant VM with mysql, nginx, puma, ruby and install the linked application.

# Usage

Update the variable in playbooks/vars/vars.yml
Place the Vagrant file at the root of the ruby installation.
Place the playbooks folder at the root of the ruby installation.
```vagrant up```

# Customisation

Most customisation (if needed) will happen in playbooks/tasks/deploy_application.yml for customer ruby / gem install commands.

# TODO

Target non-vagrant box
Structure customisation options a little better
Implement other server options
Make Vagrant file more better (local port forward? dns for multiple
machines?)
Roles?

