I opened up my terminal and connected to my virtual server using `ssh`

![](./img/1.ssh.png)

I tried to create a directory in the home directory of the root user but was denied because I didnt have permission

![](./img/2.mkir-failed-permission.png)

I then used the `sudo` command to run the same command and this time it was successful

![](./img/3.mkir-success.png)

I then confirmed the folder had been created by listing the contents of the `/root` folder

![](./img/4.folder-confmatn.png)

I used `pwd` to find the path of my current working directory

![](./img/5.pwd.png)

I then switched to the root directory and listed its contents

![](./img/6.root-directory.png)

![](./img/7.ls-root-directory.png)

I followed that up by switching to the `/usr` folder, I created a directory called `photos`, I then switched to the photos directory and created 3 more directories called dir1, dir2 and dir3.
I switched to dir1 and showed the file pth using the `pwd` command

![](./img/8.cd-usr.png)

![](./img/9.photos-directory.png)

![](./img/10.dir-in-photos.png)

![](./img/11.file-path-dir1.png)

I then viewed the files and directories in my documents folder using the `ls` command on my Documents folder

![](./img/12.ls-documents.png)

I used the cat command to view the contents of the `os-release` file in the `etc` directory

![](./img/13.os-release-file.png)

I created a foldder called `file.txt` and copied it into the Documents folder using the `cp` command

![](./img/14.cp-file-to-folder.png)

I then created 3 more files called file1.txt, file2.txt, file3.txt and copied them into the Documents folder. I then copied the contents of a file into another file as well as copied contents of a directory into another directory

![](./img/15.cp-multiple-files-to-folder.png)

![](./img/16.cp-content-of-file-to-another.png)

![](./img/17.cp-content-of-dir-to-another.png)

I then moved file.txt to the Documents folder using the command `mv`. I used the same cmmand the renme the file to firstfile.txt. I followed that up by using the `rm` command to delete file.txt, and subsequently used it to delete file1.txt, file2.txt and file3.txt. I then used the `touch` command to create a web file in the Documents directory. 
Finally I used the `find` command to file a file using its name in the home directory and all its sub directories

![](./img/18.rem-commands.png)