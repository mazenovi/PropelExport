PropelExport
================

Fork of [PropelExport] (http://www.diloc.de/blog/2008/05/27/mysql-workbench-propel-export-plugin/), 
[lua] (http://www.lua.org/) script 

Installation
------------

### For old MySQLWorkbench versions

Copy the file to your modules-folder inside the Workbench installation. 
This should work in all versions of Windows prior to Vista.
On Vista this may not work due to the automatic directory-redirection. 
In that case place the file into that folder: C:\Users\<username>\AppData\Roaming\MySQL\Workbench\modules\ and it should work perfectly.

### For old MySQLWorkbench 5.2 (current)

"Scripting" -> "Install Plugin / Module" 
select "lua files (*.lua)" or "All files (*.*)" for file's type filter and browse to PropelExport.grt.lua

In both case you have to restart MySQL Workbench to use it!

Use
---

* Plugin should show up in the "Plugins" -> "Catalog menu", or at right click on table. 
* all entries from the plugin are prefixed with “PropelExport:” so you should be able to find them easily.

What's New In PropelExport 0.6
------------------------

* Works with Workbench 5.2
* Added behaviors can be set in table's comment as <behaviors>...</behaviors>
* Added single inheritance can be set in columns's comment as <inheritances>...</inheritances>
* Added support to set package manually
* Fix some indent bugs in XMLWriter:addContent()