Description
-----------
This module adds the ability to submit content from a webform and someto eloqua.com content type to your Drupal site.

Requirements
------------
Drupal 6.x, and webform and fieldgroup modules.

Installation
------------
1. Copy the entire webform_eloqua directory the Drupal sites/all/modules directory.

2. Login as an administrator. Enable the module in the "Administer" -> "Site
   Building" -> "Modules"

3. (Optional) Add a group called (group_)eloqua_submit to your CCK content types. Any fields in this group will also be sumitted to eloqua along with the webform that is submitted from the node's page.
