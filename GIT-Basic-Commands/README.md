# GIT Basic Commands

## GIT

First of all I installed GIT on my device

![git](./Img/1.git.png)

## GIT HUB Repository

I followed that up by creating a GITHub repository called `ai-startup-website`

![githubrepository](./Img/2.gitrepository.png)

## GIIT Project Folder

I went to my terminal, then went to my folder where I store all Darey.io work and created a folder called `git-project`

![git-project](./Img/3.git-project.png)

I switched folder to the git-project folder 

![cd git-project](./Img/4.cd%20git-project.png)

I subsequently cloned the git repository, ai-startup-website, into the git-project folder I created

![gitclone](./Img/5.gitclone.png)

I switched to the ai-startup-website repository and created a html file called index.html

![index-html](./Img/7.index-html-file.png)

I added content to the index.html file

![content-in-index-html](./Img/8.content-in-index-html.png)

I saved and exited the file, then i checked the status of the file to show it had not been staged 

![gitstatus-no-staging](./Img/9.gitstatus-no-staging%201.png)

I then staged the index.html file by using the command `git add`

![gitadd-index-html](./Img/10.gitadd-index-html.png)

I checked the status of the index.html file again to confirm it had been staged succesfully

![gitstatus-staged](./Img/11.gitstatus-staged%201.png)

I then commited/saved the file using the command `git commit`

![gitcommit](./Img/12.gitcommit.png)

I followed that up by pushing the file to the GIT Hub repository

![gitpush](./Img/13.gitpush.png)

I checked the branch I was working on and confirmed it was the main branch

![gitbranch](./Img/14.gitbranch.png)


I created a new branch for Tom's work called `update-navigation` and automatically swithed to it using the command `git checkout -b update-navigation`

![Toms branch](./Img/15.Tom's%20branch.png)

I confirmed my branch was now the update-navigation branch


![Tom's-index-html](./Img/16.gitbranch-update-navigation.png)


I then added content into the index.html file in Tom's branch

![Tom's-index-html](./Img/17.Tom's-index-html.png)

I exited the index.html file and checked the status of the file in Tom's branch

![gitstatus-no-staging 2](./Img/18.gitstatus-no-staging%202.png)

I then staged the file

![gitadd 2](./Img/19.gitadd%202.png)

I checked the status to confirm it had changed

![gitstatus 2](./Img/20.gitstatus%202.png)

I commited the file

![gitcommit 2](./Img/21.gitcommit%202.png)

Then I pushed it to the GIT Hub Repoitory

![gitpush](./Img/22.gitpush.png)

I subsequently switched back to the main branch 

![gitcheckout](./Img/23.gitcheckout.png)

On the main branch, i created a pull request to ensure im working with the most updated version of the files and folders using the command `git pull origin update-navigation`

![gitpull](./Img/24.gitpull.png)

I then created a new branch for Jerry's work called `add-contact-info` and automatically swithed to it.

![gitbranch 2](./Img/25.gitbranch%202.png)

I then opened the index.html file in Jerry's branch and added content to it

![jerry-index-html](./Img/26.jerry-index-html.png)

I then saved the file and exited, then staged the index.html file in Jerry's branch

![jerry-gitadd](./Img/27.%20jerry-gitadd.png)

I commited the file

![jerry-gitcommit](./Img/28.jerry-gitcommit.png)

I then pushed the file to GIT Hub repository

![gitpush 2](./Img/29.gitpush%202.png)
