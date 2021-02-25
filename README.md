# ACO Documentation Repository

------------------------------------------

## Linux

### Install Git

`$ sudo apt-get install git -y`

Setup your SSH Keys

[GitHub has a nice walkthrough](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)

Move to the directory you want to store the repo (example: ~/ or ~/Documents/ )

` $ cd ~/Documents`

### Clone repo


`$ git clone git@github.com:WYWM-ACO/documentation.git`

### Get updates

`$ git pull`

### Push your changes
```
$ git add -a #adds all your changes to the commit
$ git commit -m "this message tells us what you changed"
$ git branch -M main
$ git remote add origin git@github.com:WYWM-ACO/documentation.git
$ git push -u origin main
```

