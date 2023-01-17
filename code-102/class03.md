
# Class 03 




## GIT   ***What is Git?***

Git is a Distributed Version Control system (DVCS). It is primarily used for collaborative projects.

Key points of of Git:

- Git saves snapshots of the changing versions of your work
- Git stores your code remotely on your computer, so you don't need to be online

**Git is not the same as Github** Github is an online database that runs Git. Other Git based services are Bitbucket and Gitlab; the former being popular with business use due to it being integrated with other software. 


## Git Commands I have Used Through Ubuntu 

-To enter a folder = cd 'name of folder'

-To autocomplete = TAB

-To see which folder youre in = ls

-To go back to previous file position: cd ..

-To create a folder = mkdir 'name of new folder '

-To create a file = touch 'name of file'


### Steps to uploading to GITHUB:

1. git add . (everything) or git add 'filename'.md (md because it's mark down)
2. git commit -m "reference of change"
3. git push origin main

-To check = git status 

-To force a push = git push -f

### Steps for cloning to GIT

1. Click on file in Github
2. Click green 'code' button
3. Make sure it's on HTTPS
4. Copy the URL
5. Go to Ubuntu
6. Write command = git clone URL


- Use VSCode for all code editing, not GitHub
    If you edit in VSCode and dont save, you can work it through Ubuntu by =
        - git add .
        - git commit -m "change files names(eg)"