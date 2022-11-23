# Git command basic commands

- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#add">Add</a>
- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#remove">Remove</a>
- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#pull">Pull</a>


# Add
To add a file to the remote repository, clone the repo and put the file you want to add in it :

```bash
git clone https://github.com/Blah/blah.git
cd blah/
# Now create or copy a file in blah/
```

then git add your file with the command
```bash
git add -A
```

create the commit 
```bash
git commit -m "added the file_to_add file !"
```

and push the modifications :
```bash
git push
```

### Example :
![ADDAFILE](https://user-images.githubusercontent.com/106782577/203608593-dd9db07f-db2f-4803-9075-16a113b2b0fa.png)


**NOTE : when github ask's you for your password, put your personal access token instead :**     
https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls



# Remove

Git clone the repo
```
git clone https://github.com/Blah/blah.git
```

Rm the file you want to remove
```
git rm file_to_remove
```

Create the commit and push
```bash
git commit -m "removed file" && git push
```

### Example :

![REMOVE](https://user-images.githubusercontent.com/106782577/203609294-b3dd5761-1283-48fd-92f0-f1de57e36f3d.png)


# Pull

Get latest modification from the remote repo
```bash
git pull
```

### Example

![pull](https://user-images.githubusercontent.com/106782577/203603859-0359b738-c98b-412b-b27b-7bff2a300206.png)

