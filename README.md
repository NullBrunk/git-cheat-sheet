# Git command Cheat-Sheet

## Clone
Clone a remote repository
```bash
git clone http://github.com/Blah/blah.git
```

## Add
To add a file to the remote repository

Clone the repo and put the file you want to add in it

![cpinit](https://user-images.githubusercontent.com/106782577/203600915-9263db5e-e1f8-453f-9080-299aa7314c14.png)

then git add your file with the command
```bash
git add -A
```

create the commit 
```bash
git commit -m "added the README file"
```

and push the modifications :
```bash
git push
```

![push](https://user-images.githubusercontent.com/106782577/203602898-6964181f-ef2f-4050-84cb-5ad9e9252a16.png)

**NOTE : when github ask's you for your password, put your personal access token instead : **     
https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls


### Pull

Get latest modification from the remote repo
```bash
git pull
```

![pull](https://user-images.githubusercontent.com/106782577/203603859-0359b738-c98b-412b-b27b-7bff2a300206.png)


### Remove

Git clone the repon, cd on it, and use the `git rm` command
```
git rm nomfichier.txt
```

then you can git commit and git push

![del](https://user-images.githubusercontent.com/106782577/203604717-af431a01-5645-472e-9071-39761e6761b8.png)



