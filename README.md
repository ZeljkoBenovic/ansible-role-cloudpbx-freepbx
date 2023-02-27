# FreePBX Ansible Playbook 
This playbook installs FreePBX v16 on the Ubuntu 22.04LTS minimal server.

## Prereqisites 
* Freshly installed Ubuntu 22.04LTS minimal

## Usage
* Set your database password with `export DB_ROOT_PASS='<your_password>'`
* Run the playbook. Example: `ansible-playbook -i 172.18.223.4, -u ubuntu cloudpbx-freepbx.yaml`

After playbook completes, you server IP should have FreePBX web service running
