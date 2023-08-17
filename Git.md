Terms
---
SSH - Secured Shell


Commands
---
```bash
git init
```
Creat a git reposotory

```bash
git config -global user.name
git config -global user.email
```
Configure the username
Configure the user email

```Shell
git remote add origin example.link
```
This will give you a destination to push your work to 

```
```shell
git add readme.md
```
Will be read and tracked by the git repo

```shell
git add .
```
track all files in the reop


```shell
git clone https://github.com/Spencer-OBrien/Lucky-ducky.git
```
clone the repo onto your machine

```shell
nano readme.md
```
create a new Markdown file or open an existing file in nano

```shell
git push
```
push your work out to the repo

```shell
git checkout -b 'BranchName'
```
create a new branch

```shell
git checkout 'main'
```
move you to the main branch

```shell
git merge main
```
merge your current branch to the main branch

```shell
git status
```
see working tree status

```shell
git commit -m 'commitname'
git commit -am 'commitname'
```
commit your code
commit your code that has not been added yet

```shell
git log
git log -1
```
see a log of all commits
see the last log

```shell
git push -u origin 'BranchName'
```
update the online repo

```
```