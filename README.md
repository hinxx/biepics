# biepics

Some snippets that might come in handy..

## Local yum repo (server)

Follow instructions on http://www.itzgeek.com/how-tos/linux/centos-how-tos/create-local-yum-repository-on-centos-7-rhel-7-using-dvd.html.  
Use /var/www/html/yum/x86_64 for repo location:

	$ sudo cp *rpm /var/www/html/yum/x86_64
	$ sudo createrepo /var/www/html/yum/x86_64


## Local yum repo (client)

Copy __bipc2-yum.repo__ to client __/etc/yum.repos.d/bipc2-yum.repo__.  
Run __sudo yum repolist__ to see the repo info.  

