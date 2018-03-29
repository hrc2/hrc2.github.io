# Workflow for adding content to the site (for Collaborators)

To add content to the site, you will work on your own staging branch. Below are the steps necessary to do so using the command line. 

You can also use the github online interface or some git client, but I don't know how those work. If you use that, please add the instructions in a section below.

## Using the Command Line

**This is from memory, please update with how this works for you**

### Clone the repository

`git clone https://github.com/hrc2/hrc2.github.io.git`

### Create your own branch

`git checkout -b <yourname_staging>` 

### Make Changes, add, commit as usual

### Push your branch 

First time:

`git push -set-upstream origin <yourname_staging>`

After that, just regular

`git push`

### Create a Pull Request

This is easiest done online on github.com, but there is a `git pull-request` CLI API, which is a little annoying to use. If someone figures it out, please add here.

### To stay up-to-date with the master branch

Before your next changes, do:

```
git checkout master
git pull
git checkout <yourname_staging>
git rebase master
```

(I think that's the right way, feel free to fix if your experiance varies)
