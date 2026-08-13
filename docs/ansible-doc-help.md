Ansible provides a comprehensive documentation resource. There are several commands with multiple flags that can you find module info, configuration info, command info. 

For module documentation:
ansible-doc is by far the best tool to get get module details. You can start with ansible-doc -l which will list all the modules. From there you can search for specific modules using grep.
    -Example:
        ansible-doc -l | grep user

ansible-config is how you get most information about the ansible configuration. You can view and alter configuration details.
    -Example:
        ansible-config list

ansible-playbook --help is a tool that can help you get infomation about all the flags related to ansible-playbook

These are some of the main tools that can used to navigate ansible. There are several more. You can find more in depth documentation at www.docs.ansible.com
           
