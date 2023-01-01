# Git basic commands

- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#add">Add</a>
- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#remove">Remove</a>
- <a href="https://github.com/NullBrunk/git-cheat-sheet/blob/main/README.md#pull">Pull</a>


# Add
To add a file to the remote repository, clone the repo and cd in it :

```bash
git clone https://github.com/Blah/blah.git
cd blah/
```
Now **create / edit / copy** a file in the git directory (in this example : blah/), for example :

```bash
echo "Hello World" > hello.txt
```

then to "execute" all the modifications :

```bash
git add -A    # To add all the modified file
git commit -m "added the file_to_add file !"     # commit the modification
```

you have an alias for this

```bash
git commit -am "Added and commited in one command !"
```

if you have any problem with your git commit command (like the message for example)
you can use git commit --ammend

```bash
git commit --ammend -m "Changing the commit message ..."
```

then you can push the modifications :
```bash
git push
```

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


# Pull

To get latest modification from the remote repo you can use :

```bash
git pull
```

