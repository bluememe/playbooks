# playbooks
playbooks

this are files using for custom chrooted apache configuration in /chroot directory
create template folder and copy jinja2 template in that directory

keep apache-install-with-variable.yml file outside the template folder


below are the variables used in this play and template


appuser --user for http

servername  -- details of host

apache_file -- tar file to copy specify with version

http_instance -- http directory name

apache_port -- port to use for apache

Note: check syntax before running its still in development
