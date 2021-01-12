# Sanbox

## What is Sandbox
This is just a repo to experiment with git.
Try making a pull request.

Change this README.md or add a new file.

## Hints
Install git: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Clone this repository (use the green Code button at the top right).

Fork this repository (click the fork button at the top right 
    (even more top right than the code button))

Add the address of your fork to your local git as a `remote`.
If you are using the command line it's something like this:
```
git remote add myfork git@github.com:your-git-id/sandbox.git
```

You can read more about forks here: https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/working-with-forks

Now create a branch on your local machine. Make some changes. Commit the changes and push them
up to your fork.
If you change this readme for example:

```
git checkout -b update-readme
git commit -s REAME.md -m 'Updated description'
git push myfork update-readme
```

Now if you go back to your browser you'll see a pull request button available (on either the
original repo or on your fork). 

## Hint 2

If you are collaborating on a text file document (like this one) the web-based interface seems relatively easy to use.

## Hint 3

I discovered three ways of getting to this one file and i tried all three of them. Was only able to use the browser to update the file. Need to figure out how to do it using the other two mechanisms (cmd line nad Git GUI)
