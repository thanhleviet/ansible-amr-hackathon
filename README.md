ansible script to setup VMs fro CLIMB-AMR-HACKATHON
## What it does?
- Create group hackathon
- Create users from a list of users with predefined Username, Password, Host (see the template users.csv.tpl, the column Domain is optional)
- Install centralised conda
- Install singularity

## Command:
```bash
ansible-playbook -i host setup.yaml
```