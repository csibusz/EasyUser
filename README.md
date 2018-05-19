# EasyUser
Login and registration php and mysqli
Installation EasyUser script

Step 1. Create database and upload easyuser.sql. (location: sql/easyuser.sql)
------------------------------------
Step 2. Open and edit config.php file Database connect and pagination item per page (location: include/config.php)
------------------------------------
Step 3. upload all the files to your storage 

First Login

Login to your website www.yourdomain.com. Click login bottom

Default Username:admin@admin.com Password:111111
------------------------------------
After entering

Default content and website setting edit 
Source Codes Edit
Site data:  Website name: $sitename Website meta: $sitemeta Website registration live: $sitereglive Website email: $sitemail Website term of use: $siteterm 
------------------------------------
User data:  User is login: $_SESSION['login']  Username: $_SESSION['username']  Userid: $_SESSION['id']  User email: $_SESSION['email'] User privilages (admin): $_SESSION['superuser'] User password: $_SESSION['pass'] 
------------------------------------
Functions:  User and visitors ip: user_ip() User OS : user_os() 
Footer Text
