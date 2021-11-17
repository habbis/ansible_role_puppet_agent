setup puppet agent 
=========

This role setup puppet agent for a puppet server but in my case i use it for foreman server.


Role Variables
--------------

Here is a list for variables.

puppet server name should be placed here.

puppet_server

ubuntu puppet deb package 

ubuntu_debfile

debian puppet deb package

debian_debfile

rhel rpm package

rpmfile

the package to install 

package

the service to enable and start

service

If true delete puppet ssl dir if having ssl issues

delete_puppet_ssl_dir: false

If set to true will remove puppet-agent and remove package

apt_purge: false

same as apt purge 

yum_purge: false

if true will  trigger a puppet run

run_puppet_agent: false

if true will fix  /etc/hosts 

fix_hosts: false

