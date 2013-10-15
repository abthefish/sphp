2013.10.14
o notes from running sphp install (from browser)

We think your blog is at localhost/sphp/.

41 If not, set BASEURL correctly in scripts/config.php

PHP Configuration Checks:

NOTE: Maximum size for image uploads is 2 MB. Adjust upload_max_filesize and post_max_size in php.ini to larger values if you need to upload bigger files.

<?php
	// Save file as 'password.php' and FTP it into the 'config' directory.
?>

- did chown to www-data, and chmod to 600

Note: If you want to reset your username and password (probably because you forgot it), delete the password.php file in the config folder on your web site. The next time you visit your site, it will walk you through this installation process again...


Login
Congratulations!
You are now logged in.

Click below to visit the Setup page, where you can personalize your new blog.

Note: Now that you've completed the installation process, it is recommended that you delete the installXX.php files from your web site. (i.e. install00.php through install06.php)

