blog
====

Open Source Blog

#### Operating Environment
* PHP 5.2.17 or higher
* MySQL 5.1 or higher


#### Installation

1. Download the .git or .zip file, and extract it to the server.  
app  
public [public directory]  
　  
2. Change the name of the settings file, and store the DB or Server information.  
public/config.php.sample -> public/config.php  
　  
 *If the app directory does not exist on the same level as the public directory,  
you will need to amend the path from the following area in the config.php file.  
require(dirname(__FILE__) . '/../app/core/bootstrap.php');  
　  
3. Access the Installation Screen  
[DOMAIN]/admin/install.php  
　  
4. Follow the instructions and complete installation.  
　  
5. Once installation is complete, admin/install.php will no longer be necessary. Please delete it.

*Do not remove the link to FC2 in the template.
