Role Name
=========

Installs wp-cli (http://wp-cli.org) and adds it to the path

Requirements
------------

Just PHP

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Defaults:

To Force update / reinstall
wpcli_reinstall: no
To change the download url:
wpcli_url: "https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar"
To change the destination:
wpcli_dest: "/usr/local/bin/wp"



Dependencies
------------

None hardcoded, but requires PHP. If in doubt, run geerlingguy.php first

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: bvansomeren.wpcli }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
