github_call_api
=========

This role is a collections of plays that call the GitHub api.

Requirements
------------

Git >= 1.7.1 (command line tool) is required to be installed.  The `github_list_repositories.yml` installs *JMESPATH* in order to process the Json data returned by GitHub.

Role Variables
--------------

No variables are set in the `defaults/main.yml` or `vars/main.yml` files.

| Play | Inputs | Outputs |
|----------|----------|----------|
| github_clone_repository | `git_repository_url` </br> `git_clone_folder`| None |
| github_list_repositories | `git_user` | `git_repository_list` |


Dependencies
------------

None.

Example Playbook
----------------

Each play contains instructions on how to use it.  Copy the usage details, uncomment, indent as required and change the variable values as appropriate.

License
-------

Apache

Author Information
------------------

Ian Turner </br>
Snr DevOps Technician
