# Linux Fundamentals

I visited to AWS website and created a new AWS account and went ahead to launch an EC2 instance 

![](./Img/1.new-instance.png)

I then took the public IP address of the instance and opened up my Mobaxterm, opened the terminal, changed directory to the `Downloads` folder which contains my pem key and connected to the virtual server I created on AWS using `ssh`

![](./Img/3.switch-directory.png)


![](./Img/4.ssh-to-virtual-server.png)

I updated the existing packages, installed tree command, verified the tree command had been installed by using it on some directories.

![](./Img/5.sudo-apt-update.png)

![](./Img/6.sudo-apt-update-2.png)

![](./Img/7.install-tree-command.png)

![](./Img/8.tree-command-home.png)

![](./Img/9.tree-command-downloads.png)

I then updated the packages I had installed and followed that up by removing the tree command

![](./Img/10.sudo-apt-upgrade.png)

![](./Img/11.sudo-apt-upgrade-2.png)

![](./Img/12.sudo-apt-upgrade-3.png)

![](./Img/13.sudo-apt-upgrade-4.png)

![](./Img/14.removing-tree-command.png)


Lastly I installed `Nginx` on my virtal server

![](./Img/15.install-nginx.png)


