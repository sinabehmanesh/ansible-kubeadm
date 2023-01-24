KubeAdm
=========

this ansible role will setup kubernetese cluster and join workers to it
it will make sure everything is healthy and ready to use
**this version does not support docker as CRI**

Requirements
------------

* at least 2 ubuntu instances with minimum 2GB of RAM and 1 core of CPU.
* stable internet connection.
* this version of role does not support IP tables and firewall configurations, please allow k8s ports in your firewall.
Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.


License
-------

BSD

Author Information
------------------

developed by Sina behmanesh.
>>>>>>> dev
