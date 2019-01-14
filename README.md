 Ansible role to install dokuwiki
---------------------------------
An ansible role to install dokuwiki.

It will simply download dokuwiki to ``/var/www/{{ dns_name }}/`` and you can call install.php like usual.
It will prevent you to overwrite the file by placing a ``do_not_delete.txt`` file. As long this file is unchanged, it won't download and extract dokuwiki again.


 Nice to have, but not implemented:
--------------------------------
 - Check the checksum from dokuwiki
 - configure dokuwiki via ansible
 - user management via ansible


 What you need to do by hand
-----------------------------
This role dosn't configure dokuwiki or will delete the install.php.
You have to expand this role for this or do it by hand!

