# Hacktoberfest Week 2!

![Hacktober Fest Image](https://user-images.githubusercontent.com/121322/45653341-78d1c000-ba8c-11e8-9497-2855130c0634.png)

#### Note
Before continuing make sure that git is installed on your machine!!
There are plenty of resources out there such as...

- [This Simple Blog](https://gist.github.com/derhuerst/1b15ff4652a867391f03)
- [or This 20 Minute Video](https://www.youtube.com/watch?v=J_Clau1bYco)

While both are helpful tutorials, you might run into some problems. If so you are more than welcome to stop by our [Slack channel](https://pymavs.slack.com/join/shared_invite/enQtNDU2MzEwODEyMjE1LWQ1MzcxOTgwNDMwOWVlY2U3MTJjNjIzZGYyNjQxZDgwMTVjOGEwMzNiZjcxYTgxNDE5NWQ4NGVkNjM0MWY4OTI) for some one on one help.

---

## Step 1
#### Link your account to [https://hacktoberfest.digitalocean.com/](https://hacktoberfest.digitalocean.com/) !!!

[Signing up](https://hacktoberfest.digitalocean.com/) by linking your Github account will make sure that DigitalOcean can track any pull requests you make. The goal for us is to make 4 pull requests. It does not matter if you're fixing a complex problem or simply editing the documentations. The goal of Hacktoberfest is to learn how you can support any opensource project.




## Step 2
#### [Find an issue!](https://github.com/search?q=label:hacktoberfest+state:open+type:issue)

Some projects out there are simple and beginner friendly. If you are looking for an easy issue to fix, you could always check out our [Websites Github Link](https://github.com/PyMavs/pymavs.github.io). There should be some easy to fix HTML/CSS fixes that you can pull.




## Step 3
#### Fork The Repository

Forking an issue creates a copy of the repo on your account. In otherwords, all the code gets copied to your Github account allowing you to mess with it anyway you want. The next step is to get that code onto your computer!

![Image of Fork Button](http://readme-pics.s3.amazonaws.com/fork_button.jpg)




## Step 4
#### Download The Code

To download your fork, copy the url address or click on the green "Clone or Download" button and copy that url.

![Image of Download](https://help.github.com/assets/images/help/repository/remotes-url.png)


Then on your terminal, cd to the destination you want to download the code to and run...

``` bash
  git clone https://github.com/PyMavs/pymavs.github.io.git
```
but with the URL you copied.



## Step 5
### Fix the issue

Check the documentation page to see how to run the code, then find the issue and fix it!



## Step 6
### Commit Your Changes

By commiting, we are saving everything we changed on our computer. To do this run

``` bash
git add .
git commit -m "Your message goes here inside the quotes"
```
**git add .** adds everything that you edited
**git commit -m "string goes here"** saves your changes with the string describing what you did. Make sure the message is descriptive!



## Step 7
### Pull Request

The final step is to finally make a pull request.

![Pull Request Image](http://s3itch.paperplanes.de/travis-ci_travis-ci.github.com_at_mm-pull-requests-workflow-20120813-103348.png)

---

# High level view of Git version control:

![Git Flowchart](https://i.stack.imgur.com/nWYnQ.png)


# Git Commands

### To add your git credentials and login information (Do this first if you haven't yet!)
``` bash
git config --global user.name "FirstName LastName"

git config --global user.email your.name@mail_server.domain.com
```
Make sure this information matches what is on your Github account!

### Initialize a new local repository (only do this if you are starting from scratch)
``` bash
git init
```

### Check your repo status
``` bash
git status
```

### View changes
``` bash
git log
```

### View changes (with more detail)
``` bash
git log --summary
```

### Preview changes *before* merging
``` bash
git diff [source] [target]
```

### To clone a repository
``` bash
git clone https://github.com/Path/toRepository.git
```
Of course, use the *real* URL that corresponds to the project or repository you want to work with.

### Add all new *and* changed files to the staging area
``` bash
git add -A
```
or
``` bash 
git add .
```

### To commit and save
``` bash
git commit -m "[enter your comments or description of the changes here]"
```

### Add a single file to the staging area
``` bash
git add [file-name-goes-here.extension]
```

### Push a branch to *your* remote respository
``` bash
git push origin
```

### Update a local repository to the newest commit of the remote repository
``` bash
git pull
```

