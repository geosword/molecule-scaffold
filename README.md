# molecule-scaffold
A scaffold for new ansible roles tested with molecule

The main idea is making starting a new role easy including all various scripts and things I've created to make my life easier.

Scenario ```molecule/default/``` includes sample molecule files for docker (molecule.yml) and aws (molecule-ec2.yml) and some other standard files which might be needed for developing a role.

Read the comments in ```verify.yml``` and ```verify/*.yml``` to fully understand how to use it, and it's limitations
