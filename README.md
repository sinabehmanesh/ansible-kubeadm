KubeAdm
=========

this ansible role will setup kubernetese cluster and join workers to it
it will make sure everything is healthy and ready to use


Requirements
------------

* at least 2 ubuntu instances with minimum 2GB of RAM and 1 core of CPU.
* stable internet connection.
* this version of role does not support IP tables and firewall configurations, please allow k8s ports in your firewall.
Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

CNI
------------
this play book will deploy calico as CNI. if you prefer another one, them edit kubeadm-init.yml file of just deploy manually.
CIDR used for cluster initialization is 192.168.0.0/16.
if you want to change that, edit file and for more info check calico documentation(or any other CNI providre you want to deploy).

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

CRI
------------
default containerd CRI is included. i will replace it with CRIO as main CRI.
optional CRI will be available in the next updates.

**this version does not support docker as CRI, only Containerd is included**

License
-------

BSD

Author Information
------------------

developed by Sina behmanesh.
>>>>>>> dev
