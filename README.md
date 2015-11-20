# JupyterHub deployment for Colaberry Test class

This repository contains an Ansible playbook for launching JupyterHub for the
Colaberry Data Science experimental class. It is almost entirely based on the deployment for [Computational Models of Cognition](https://github.com/compmodels/jupyterhub-deploy) and (https://github.com/ryanlovett/jupyterhub-deploy). Compmodels course utilized Rackspace infrastructure and GitHub for authentication while Ryanlovett deployment used AWS and Google OAuth. There are also some minor changes in the docker and NFS configurations.

I am still working on makig this work with adhoc servers and Goole OAuth.

For detailed information, please see @jhamrick's README.md in the compmodels repository linked above.
