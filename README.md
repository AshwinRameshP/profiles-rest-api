# Profiles REST API

Profiles REST API course code.

# Software requirements
Virtual Machine -Oracle VM box
Git
Vagrant

#Setting up Project requirements
## Vagrant VM
'vagrant up'   -- initiates vagrant virtual boxes
'vagrant ssh'  -- Sign in into virtual Machine

## Create python venv
'python -m venv  ~/env'     -- initialise python virtual development Environments
'source ~/env/bin/activate' -- Activate the python virtual environment
(env) pip install -y requirements.txt -- initialise django and REST framework dependencies in venv
(env) 'deactivate'          -- deactivate virtual env
