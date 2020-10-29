# MentHealth

![](images/Logo.png)

:wave: Welcome to **MentHealth**! We are an open source community 
which helps in spreading awareness about mental health and depression among teens and young adults.This is a non-profit initiative to fight against this cause.

Show some :heart: and :star: this repository!
 
## Wish to contribute to this repository? :sparkles:
Welcome for contribution to this repository so that students from across the :earth_asia: could be benefited. I also advise you to take a look at [CODE OF CONDUCT](https://github.com/Anurag5086/MentHealth/blob/master/CODE_OF_CONDUCT.md) and [CONTRIBUTING](https://github.com/Anurag5086/MentHealth/blob/master/CONTRIBUTING.md). Here are the steps to help you along :scroll:

### 1. Fork this repository :fork_and_knife:
You can get your own fork/copy of [MentHealth](https://github.com/Anurag5086/MentHealth) by using the <a href="https://github.com/Anurag5086/MentHealth/new/master?readme=1#fork-destination-box"><kbd><b>Fork</b></kbd></a> button


### 2. Clone this repository :busts_in_silhouette:
You need to clone (download a copy of) this repository to your local machine using:
```sh
$ git clone https://github.com/YOUR_USERNAME/MentHealth.git
```
> This makes a local copy of repository in your machine.
Once you have cloned the `MentHealth` repository in GitHub, move to that folder first using change directory command on linux and Mac.
```sh
# This will change directory to a folder Python3-by-practice
$ cd MentHealth
```
Move to this folder for all other commands.


### 3. Set it up :wrench:
Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in GitHub :octocat:
```sh
$ git remote -v
origin  https://github.com/YOUR_USERNAME/MentHealth.git (fetch)
origin  https://github.com/YOUR_USERNAME/MentHealth.git (push)
```
Now, lets add a reference to the original [MentHealth](https://github.com/Anurag5086/MentHealth) repository using
```sh
$ git remote add upstream https://github.com/Anurag5086/MentHealth.git
```
> This adds a new remote named ***upstream***.
See the changes using
```sh
$ git remote -v
origin    https://github.com/YOUR_USERNAME/MentHealth.git (fetch)
origin    https://github.com/YOUR_USERNAME/MentHealth.git (push)
upstream  https://github.com/Anurag5086/MentHealth.git (fetch)
upstream  https://github.com/Anurag5086/MentHealth.git (push)
```


### 4. Ready, Set, Go!!! :turtle::rabbit2:
Once you have completed these steps, you are ready to start contributing by checking Issues and creating [pull requests](https://github.com/Anurag5086/MentHealth/pulls).


### 5. Create a new branch :bangbang:
Whenever you are going to make contribution. Please create separate branch using command and keep your `master` branch clean (i.e. synced with remote branch).
```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b Folder_Name
```
Create a separate branch for contribution and try to use same name of branch as of folder.
To switch to desired branch
```sh
# To switch from one folder to other
$ git checkout Folder_Name
```
To add the changes to the branch. Use
```sh
# To add all files to branch Folder_Name
$ git add .
```
Type in a message relevant for the code reviewer using
```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```


### 6. Push your awesome work to your remote repository :rocket:
```sh
# To push your work to your remote repository
$ git push -u origin Folder_Name
```
### 7. Finally, make a PR! :fire:
Go to your repository in browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious effort.