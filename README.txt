The Basics
==========
Users in roles possessing the 'share permissions' permission are given the ability to access the permissions administration page like a user with 'administer permissions', but they can only see permissions that exist in one of their roles.

No configuration necessary (or available), except for granting selected roles the 'share permissions' capability at http://example.com/admin/user/permissions (where example.com is the URL of your web site).

Installation
============
Installing Permit own permissions (pwn) is pretty straightforward. Just copy the pwn directory into your web site's /sites/all/modules directory. Then, activate the module by visiting http://example.com/admin/modules (where example.com is the URL of your web site).

(For even easier installation of this and other Drupal modules, use Drush: http://drupal.org/project/drush )

Requirements
============
Permit own permissions requires Drupal 6 or later, though there's no reason it couldn't be backported.
