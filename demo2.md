# Creating a File from desktop and upload in Github

In order to upload a Directory, created on your desktop, in Github it's needed:

1.In Terminal using `cd .. [name of directory]/` to navigate to the directory

2.Then type `git init` in order to initialize git repository in the folder.

3.Now we are able to use `git status` & `git add .` (or) `git add [file name]`

4.We move to commit with ``git commit -m [title] -m[description]``

5.Here we should use `git push` but before we need to connect this folder to a repository in Github.
    
    5.1. So we create a new repository on Github and copy the **HTTPs** or **SHH** link.
    5.2. In the Terminal type `git remote add origin [HTTPs / SHH link]`
    5.3. Then you can check if that worked using `git remote -v` 
   
6. Now we use `git push -u origin master` in order to upload it. `-u`makes that by default everything be uploaded in the _master_ and then just type `git push`.