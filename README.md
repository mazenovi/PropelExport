PropelExport
================

Fork of PropelExport http://www.diloc.de/blog/2008/05/27/mysql-workbench-propel-export-plugin/

Installation
------------

Copy the file to your modules-folder inside the Workbench installation. This should work in all versions of Windows prior to Vista.
On Vista this may not work due to the automatic directory-redirection. In that case place the file into that folder: C:\Users\<username>\AppData\Roaming\MySQL\Workbench\modules\ and it should work perfectly.

After you placed the file into the directory, simple restart MySQL Workbench and the plugin should show up in the Plugins -> Catalog menu. The two entries from the plugin are prefixed with “PropelExport:” so you should be able to find them easily.

Thats it! Now go ahaed and test the plugin, and report how it works through the comments section! Thanks!

What's New In PropelExport 0.6
------------------------

* Works with Workbench 5.2
* Added behaviors can be set in table's comment as <behaviors>...</behaviors>
* Added single inheritance can be set in columns's comment as <inheritances>...</inheritances>
* Added support to set package manually
* Fix some indent bugs in XMLWriter:addContent()