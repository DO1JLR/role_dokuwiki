 Ansible role to install dokuwiki
---------------------------------
An ansible role to install dokuwiki.

It will simply download dokuwiki to ``/var/www/{{ dns_name }}/`` and you can call install.php like usual.
It will prevent you to overwrite the file by placing a do_not_delete.txt file.

Id ansible detects the file is gone or changed, it will download dokuwiki again.

 Nice to have, but not implemented:
--------------------------------
 - Check the checksum from dokuwiki
 - configure dokuwiki via ansible
 - user management via ansible

