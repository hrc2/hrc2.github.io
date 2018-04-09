# Workflow for adding content to the site (for Collaborators)

To add content to the site, you will work on your own staging branch. Below are the steps necessary to do so using the command line. 

You can also use the github online interface or some git client, but I don't know how those work. If you use that workflow, please add the instructions in a section below.

## Using the Command Line

**This is from memory, please update with how this works for you**

### Clone the repository

`git clone https://github.com/hrc2/hrc2.github.io.git`

### Create your own branch

`git checkout -b <yourname_staging>` 

### Make Changes, add, commit as usual

### Push your branch 

First time:

`git push --set-upstream origin <yourname_staging>`

After that, just regular

`git push`

### Create a Pull Request

This is easiest done online on github.com. There is a `git pull-request` CLI API, which is a little annoying to use and gets you halfway there. If someone figures out a good CLI workflow, please add the information here.

### To stay up-to-date with the master branch

Before your next changes, you need to either rebase your branch from the current master, or create a new branch for every change you made. This is up to you. The new branch can't be named the same as the old one. So you would want to use a different name for each addition you make to the website. Please use informative names. 

```
git checkout master
git pull
git checkout <yourname_staging>
git rebase master
```

(I think that's the right way, feel free to fix if your experiance varies)
