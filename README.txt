Roles are in separate folders and contain yaml file with instructions and other folder if necessary.

main.yml is master file in which roles are/can be included. Example:

- hosts: testground
  vars:
    ansible_python_interpreter: "/usr/bin/python3"
  roles:
    - role: pbis
