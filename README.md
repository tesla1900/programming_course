j Programming in Python BCGS Summer 2022
This is the repository of Shravani, PAarth and Moritz (SPAM), to work on exercises and projects together.

## Here are some important things to note
- The main/master branch is called the "main" branch. This is the branch in which we will make the final files that will be submitted. 
- If you want to write your own code for practice, you can either do that in some other local folder, or better, create a branch in this repo and work on it over there. Then we can pick code blocks from each branch and merge it into the main branch for submission.
- In this repository, I have added the official course directory as a submodule. For more information on how submodules work, check out [this link](https://git-scm.com/book/en/v2/Git-Tools-Submodules). Because cloning a repo with submodules is a bit different, I will highlight a few keys steps below.

## How to clone this repository
```
git clone https://github.com/tesla1900/programming_course
```
This will clone the directory but will not contain that information about submodule. To do that, run the following: 
```
cd DbConnector
git submodule init
git submodule update
```

Another, much simpler way to do this is the following: 
```
git clone --recurse-submodules https://github.com/tesla1900/programming_course
```
This should set-up the repo with the submodules automatically. 

## Pulling changes to the submodule (should be done every week)
`git pull` will only pull changes made to this repo, not the submodule. In order to pull changes for that as well, run the following: 
```
cd Programming_in_Python_BCGS_Summer_2022 
git pull
```
To push these changes to the main/branch, do so by doing the usual, add, commit and push. 

## Git and github
Lastly, if you want to refresh your git and github, you can refer to these two notion articles: [git](https://www.notion.so/zarkom/Introduction-to-Git-ac396a0697704709a12b6a0e545db049) and [github](https://www.notion.so/zarkom/Introduction-to-GitHub-202af6f64bbd4299b15f238dcd09d2a7#d3eed927ff77484b84005d0e06709888). 


