# Dev

This script automation to install acpache2 application and ensure that apache2 service is enabled and running. it helps to take log backup of /var/log/apache2/ and place the tar into the /tmp/ director with timestamp. And it helps to copy tar logs into S3 bucket. script checks for the presence of the inventory.html file in /var/www/html/; if not found, will creates it. This file will essentially serve as a web page to get the metadata of the archived logs.
