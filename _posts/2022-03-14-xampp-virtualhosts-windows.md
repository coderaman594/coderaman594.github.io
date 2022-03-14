---
title: How to create, setup and enable the local virtual host in XAMPP Server on Windows
  10
---

![https://medium.com/@coderaman594/how-to-create-setup-and-enable-the-local-virtual-host-in-xampp-server-on-windows-10-60d377a94b6c](http://)

In This Article, we will learn How to Create, Setup and Enable a Virtual host in XAMPP On windows by following the below simple steps:

1. First We need go to XAMPP’s apache directory then navigate to conf\extra named folder:

> F:\coding\apache\conf\extra

2. Open ‘httpd-vhosts.conf’ named file and paste your expected virtual host URL:

#For Example virtual host URL: localhost.coderaman594.com
<VirtualHost *:80>
ServerAdmin webmaster@localhost.com
DocumentRoot F:\coding\htdocs\coderaman594
ServerName localhost.coderaman594.com
</VirtualHost>

![https://miro.medium.com/max/590/1*FKPFTUxrS1G3Z4Irf1L_JA.png](http://)

3. Navigate to etc directory-

> cd C:\Windows\System32\drivers\etc\


4. Edit the hosts named file in editor with administrator permissions then put your localhost url with ip address:

> 127.0.0.1 localhost.coderaman594.com

![https://miro.medium.com/max/587/1*tXa-8oBss2QjVbc3ha67dw.png](http://)

5. Finally, Restart your apache service with the help of XAMPP control Panel, and try to check your localhost URL in any web browser.

![https://miro.medium.com/max/667/1*k4wGk54cCnUu1s9nqr32nw.png](http://)

![https://miro.medium.com/max/700/1*cQetngQjfAe-Io-VerdFyw.png](http://)
