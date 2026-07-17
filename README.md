# rhce-lab
=======
This is a repository to document my learning journey for the RHCE EX294 exam.
I will be utilizing 6 VM's hosted on Proxmox. The VM specifications are:
Control Node
    • OS: Rocky 10 minimal
    • RAM: 2GB
    • Storage: 15GB
    • Network: Bridge
4 Managed Nodes
    • OS: Rocky 10 minimal
    • RAM: 1GB
    • Storage: 15GB
    • Network: Bridge
1 Managed Node
    • OS: Rocky 9 minimal
    • RAM: 1GB
    • Storage: 15GB
    • Network: Bridge
**This lab structure may expand with additional nodes

In the ansible.cfg file I purposely disabled the "host key checking" option. This makes connecting to my managed node easier but I will enable in the future.
