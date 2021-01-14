# Cypress-Hack-Club-Git101-Public


## Outline

- prerequisites
  - github account
    - send github usernames in teams chat
  - vscode installed
  - git https://git-scm.com/download
    - (windows only) git bash
  - (optional) cypress standalone  https://download.cypress.io/desktop
  - (optional) gitlens vscode extension 
  
- What is git and Why (distributed, branching) https://git-scm.com/doc
  - distrubuted version control vs centralized
  - branches?
    - multiple versions without copying
    - time travel
  - commits?
  - diffs not whole copies
- workshop
  - verify git 
    - git --version
  - git first time config https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
    - git confit --list
    - git config --global user.name <your name> 
    - git config --global user.email <your github email>
  - clone the shared repo
    - git clone https://github.com/the-container-store/Cypress-Hack-Club-Git101-Public.git
    - make a new branch 
      - git checkout -b <myname>/my-first-branch
    - lets setup the vscode terminal
      - cmd + j
      - select default shell
        - maybe this is needed on windows? https://www.mmbyte.com/article/9105.html
    - make our first changes
      - make a directory called <myname>  
      - make a new file called hello.md or hello.txt
      - write something int that file
    - make our first commit
      - DOUBLE CHECK the branch that we are on 
        - git status
        - git branch
      - git add .
      - git status
      - git commit -m <my first commit message!!!>
    - push our branch to github 
      - git status
      - git push 
      - copy the full command from the output 
    - Lets make another commit to our branch
      - same as above
    - Our First Pull Request
      - create a pull request
      - once it is merged 
        - checkout master
        - delete your local branch 
          - list all branches 
          - git branch -d <my local branch name>

    - Lets do the same thing from vscode ui
      - DOUBLE CHECK the branch that we are on 
      - make a new branch
      - make some changes
      - add those changes
      - commit those changes
      - push the branch
      - make a pull request
      - delete your old local branch
## recap the commands that we used https://git-scm.com/docs
  - git config
  - git clone
  - git status
  - git checkout 
  - git checkout -b
  - git branch
  - git branch -d
  - git add 
  - git commit
  - git commit -m
  - git push 
  - git pull
  - git fetch 


### Things we havent covered:
  - git merge (typically we merge via a pull request instead)
  - git rebase
  - merge conflicts
  - three way merge vs fast forward merge
  - merge commits vs linear commit history
  - forking a github repo
### Helpful Vscode shortcuts https://code.visualstudio.com/docs
  - cmd + j
  - cmd + p
  - cmd + shift + p
  - cmd + b
  - cmd + ,