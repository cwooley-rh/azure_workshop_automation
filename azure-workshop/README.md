Role Name
=========

This Azure workshop role will provision and configure the correct azure resources for the Azure Hackathon Event

Requirements
------------

Will need to create the correct azure policy that restricts access to rg creation outside of the rg created by the ARO installer.

Next, this role creates the resource groups for the users following this template: "aro-" for cluster created rg's, and "user-###" for the individual user's rg

After the RG's are created, the automation will create the Users', the User's credentials and Policy Objects.

All resource creation and provisioning are to be completed utilizing the azure.Azcollection.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
