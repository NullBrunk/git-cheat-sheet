# Git command basic commands

- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#add">Add</a>
- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#remove">Remove</a>
- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#pull">Pull</a>


# Add
To add a file to the remote repository, clone the repo and put the file you want to add in it :

```bash
git clone https://github.com/Blah/blah.git
cp file_to_add blah/
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
![ASDDD](https://user-images.githubusercontent.com/106782577/203607076-a2210c2c-6465-4ef8-97a8-18ed2ed18641.png)


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

![del](https://user-images.githubusercontent.com/106782577/203604717-af431a01-5645-472e-9071-39761e6761b8.png)


# Pull

Get latest modification from the remote repo
```bash
git pull
```

### Example

![pull](https://user-images.githubusercontent.com/106782577/203603859-0359b738-c98b-412b-b27b-7bff2a300206.png)

