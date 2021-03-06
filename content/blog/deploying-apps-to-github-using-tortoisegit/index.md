---
title: Deploying Apps to GitHub using TortoiseGIT
date: "2019-03-02"
description: TortoiseGit is a Git code control client, which is based on TortoiseSVN. It is an open source software under GNU license.
---
<p align="center">
<img width="300" height="200" src="https://res.cloudinary.com/developerayo/image/upload/v1551556961/totoise_git.png">
</p>

TortoiseGit is a Git code control client, which is based on TortoiseSVN. It is an [open source](https://github.com/TortoiseGit/TortoiseGit) software under GNU license.

## Benefits of using Tortoisegit

* Tortoisegit makes it easier to clone a repository
* Tortoisegit makes it easier to upload your code from your laptop to your repository online easily with a single command line.
* Extremely easy to pull from your online repository to update your local if you are working on a collaboration project with the click of a button.
* This tool makes it easy to remove all un-tracked files from your local with the click of a button.
* And a lot more that can be found on the link below:

## How To connect TortoiseGit with Github

* Go to [github.com](http://github.com) and login
* Create a new Repository.

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557114/1.png">
</p>

* Create a remote Github repo and name it.

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557111/2.png">
</p>

<small style="color: lightgrey;">Mine has already been created so i will work with that, Just put in the name that’s all. Then click OK.</small>

Copy the line containing your project link : https://github.com/Developerayo/My-Project-testing-tortiseGIT-.git

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557113/3.png">
</p>

## Now lets head over to the TortoiseGit we installed earlier.

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557111/4.png">
</p>

Once you have got that all opened, click on generate then move the mouse all around the box to make it go faster

After clicking on generate, you will have a box like this below

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557112/5.png">
</p>

THE LOOKS SOMETHING LIKE THIS BELOW

> ssh-rsa AAAAB3NzaC1yc2EAAAABJQAAAQEAq0jmbEdOeDHZBcD8o8FvUv1lCUBJJmM0DpHz+nn7SzT4CT2PHcOBken+9L2Zz9D7bopmx033DX3/kp/84m3Ea1n/bVDEDfWve2hH6MGcaMM3KVBhMB+6j9LVludG8zYAIt+vrDI/F9f2pZv27h9DznOT+0PJg4cpOkRSFJTgI3tY4cNTWr5kTZdBONEMI+QGNtpWwr774S

Once you have this, save it in a secure file.

Do not forget you copied the link from GITHUB that has your project repository link, now lets put that in use:

<mark style="background-color: #9a69c2; color: #fff;">https://github.com/Developerayo/My-Project-testing-tortiseGIT-.git</mark>

Create a folder on desktop and name it. Mine is named Code, then create a file in the folder, Mine is named myproject. Create a text file named hi.txt and put some text in it.

lets move on to putting the github link to use

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557113/6.png">
</p>

<small style="color: lightgrey;">Now you see the hi.txt file we created, in the message box put in initial commit then click ok
</small>

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557111/7.png">
</p>

Now lets go back to that created Repo on GITHUB

Remember the link you copied from github

<mark style="background-color: #9a69c2; color: #fff;">https://github.com/Developerayo/My-Project-testing-tortiseGIT-.git</mark>

let us make use of that.

Right click on the folder you created mine is named ‘myproject’, then click on tortoisegit, followed by the push selection at the top of the list.

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557114/8.png">
</p>

## How to setup the PUSH dialog with Github

* click on the manage button it would pop up another dialog box like that below

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557115/9.png">
</p>
<small style="color: lightgrey;">Fill in the dialog</small>

* Remote: Origin
* URL: your github url you copied earlier mine is https://github.com/Developerayo/My-Project-testing-tortiseGIT-.git\
* The the ssh or putty key you saved earlier, you would have to add that file here from were you saved it
* CLICK ADD NEW

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557113/10.png">
</p>
<small style="color: lightgrey;">Just click ok</small>

It the starts pushing it to your already created GitHub Repo

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557114/11.png">
</p>
<small style="color: lightgrey;">You would have to wait a few seconds "Go grab a coffee"</small>

Lastly visit your repo on GitHub

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557115/12.png">
</p>

Hurray 🎉🎉 you just deployed your first file to GitHub using TortoiseGIT

<p align="center">
<img src="https://res.cloudinary.com/developerayo/image/upload/v1551557115/13.png">
</p>

Thanks for reading! 🔥🚀 </br>

<a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-via="developerayo" data-hashtags="developerayo" data-related="" data-show-count="false">Share on Twitter</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

