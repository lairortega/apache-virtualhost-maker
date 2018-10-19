# mkvhost
This is an utility to create virtual hosts on apache2 server.

# Usage
	# mkvhost <string HostName> <int port> <string dbusername>
Once it runs creates:

 - The virtual hosts with the name passed in the first parameter (accessible through https).
 - A database with the same name.
 - File structure in the path /var/www/html/{HOST}/{html,log}
 - Appends the new host to the hosts file (/etc/hosts)

# Requirements

 - MySQL 5.x.
 - Apache.
 - genkey (provided by crypto-utils on CentOS/Fedora)..
