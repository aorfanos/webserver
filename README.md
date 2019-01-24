# Webserver Role

### What this role does

I use this role to automate setup of a simple webserver with HTTPS and PHP support in Debian, and perform some trivial node hardening (minor modifications in SSH and fail2ban jails). This role is especially useful if you intend to use FTP within the site, or for any cause in general. In a future commit, a tag switch will be provided so that FTP packages installation can be optional.
Along with the webserver, fail2ban is installed to protect against unauthorized logins.

### What is going to be installed

- nginx
- mariadb
- fail2ban
- vsftpd
- ftp
- php7.0* (almost, check vars/vars.yaml)
