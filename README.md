# clear_cache
# Drupal clear_cache
This is a Drupal 7 module.
This basic module Clears All Drupal Cache and adds a menu item on the main admin menu,to clear cache based on user permissions.

Adds permissions for clearing Drupal cache
Note: Clearing caches is relatively harmless. Sites might slow down for a bit afterwards while the cache fills back up.
Note: There are other caches other than Drupal cache that will affect website performance. For example, some hosting services.
Note: Clear Cache does not clear web browser cache, this will need to be cleared separately. :p
Enabling this module will add a menu link titled "Clear Cache" in the administrative tool-bar at the top.

Install Instructions;
****************************************************************************
1. Download and unzip the file.
2. Drag the "clear_cache" file into your "sites/all/modules" folder. I personally like to create a "custom" folder inside "sites/all/modules".
3. Enable the "clear_cache" module and then find the people "permissions" tab. Enable it for the various user roles.
4. We should also mention that you probably do not want to enable "clear_cache" for anonymous users.

5. You should now have a "Clear Cache" menu item at the top of your admin menu.

