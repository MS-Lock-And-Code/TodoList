# TodoList

## Set Up

To set up this project, first fork this repository to your own account

Locate fork button and click on it.

Then go to your desktop and create a folder, name it {MS-Lock-And-Code} or whatever you want.

Open the folder {S-Lock-And-Code}, right click and select the option gitbash here 
(ensure you have git installed).

To make the folder a git folder, run the following command

```sh
$ git init
```

Set up your origin and upstream remotes by running the following commands

```sh
$ git remote add origin https://github.com/MS-Lock-And-Code/TodoList.git
```

```sh
$ git remote add upstream https://github.com/MS-Lock-And-Code/TodoList.git
```

Pull the code to your project directory and set it up by running the following command

```sh
$ git fetch upstream
```

```sh
$ git checkout master
```

## Task Submission

- At the root directory (the folder you created)
- Go to your git terminal and run the following commands:
```sh
$ git add -A
```
```sh
$ git commit -m "your commit message"
```
```sh
$ git pull origin master
```
```sh
$ git push origin master
```
- And finally, go to your forked repository and make a pull request to the upstream repository 


## Note:

To make sure you have the latest version of the repo and to update your local repository with your forked repository, run this command at least before solving or pushing new solution.

```sh
$ git pull origin master
```
## HAPPY CODING!!

