# Ansible playbook to install apache and run web-site

Its ansible playbook for install httpd on CentOS or apache2 on Debian-like systems and copy files with our site to default directory and then run it.
If web-server is already installed it skips the installation. Also, if your site's files are updated, it determines which files are updated and copies them.
