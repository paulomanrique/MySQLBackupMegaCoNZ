Backup MySQL on Mega.co.nz
===================

PHP script to backup a MySQL database and upload on mega.co.nz

Requires PHP 5.3 running on Linux.

Just set up the variables at the beggining of the file and put the script on cron.

It will generate a Gzipped file, named backup_DBNAME_Y-m-d-H-i-s.sql.gz and upload it to a mega.co.nz account specified.

Mega.co.nz functions by Julien Marchand - http://julien-marchand.fr/blog/using-the-mega-api-with-php-examples/
