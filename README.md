# Table of Contents

* [Git Version Check](#Git-Version-Check)
* [Git Initialization](#Git-Initialization)
* [Git Configuration](#Git-Configuration)
* [Adding Changes](#Adding-Changes)
* [References](#References)



<br/><br/>



## Git Version Check

You can check your Git version by running the following command line in your cmd (Windows) or terminal (Linux, MacOS).
```git
$ git --version
```
<br/>

If Git is installed in your local machine, it will return the version.
```git
git version X.XX.X.OS.X
```
<br/>

If it doesn't return the version of Git, you must [install Git](https://git-scm.com/downloads) first.



<br/><br/>



## Git Initialization

You can create an empty Git repository or reinitialize an existing one. It will convert the current directory into a Git repository.
```git
$ git init
```
<br/>

If you want to create Git repository in another directory, you can enter path, e.g., `path1/path2`.
```git
$ git init <directory>
```
<br/>

If `$ git init` command is successful, it will create a hidden directory called `.git`. This directory contains objects and refs that Git uses. Also it will store commit history and other information for version control.
```git
Initialized empty Git repository in C:/Users/.../.git/
```



<br/><br/>



## Git Configuration

The `git config` is used to set the configuration values on a local, global or system level. A local level is a default setting if the level option isn't entered.
<br/><br/>

You can set the user name to "Jeon" and the email address to "email@<span></span>gmail.com" on a global level.
```git
$ git config --global user.name "Jeon"
$ git config --global user.email "email@gmail.com"
```
<br/>

Let's check the name and email configured globally.
```git
$ git config --global user.name
$ git config --global user.email
```
<br/>

Or you can bring all the global level properties.
```git
$ git config --global --list
```
<br/>

If you want to remove some properties, you can use `--unset` flag
```git
$ git config --global --unset user.name
$ git config --global --unset user.email
```
<br/>

The Git's configuration values are stored in a text file named `.gitconfig`. So, you can just use previous commands to edit your configuration values or open the `.gitconfig` text file and simply change it by using the following command.
```git
$ git config --global --edit
```



<br/><br/>



## Adding Changes

The `git add` command adds new or changed files in the working directory to the staging area.
```git
$ git add text.txt
```
<br/>

The `git add -A` command adds all changes
```git
git add -A
```
<br/>

The `git add .` command adds new and modified files, without deleted files.
```git
git add -A
```



<br/><br/>



## References

### Cheat Sheet
* [Atlassian Git Cheat Sheet](https://github.com/Yonghee9106/git-study-history/files/9484490/SWTM-2088_Atlassian-Git-Cheatsheet.pdf)

### Youtube
* [깃, 깃허브 이건 알고 사용하자](https://www.youtube.com/watch?v=lPrxhA4PLoA)<br/>
* [Git은 뭐고 Github은 뭔가요?](https://www.youtube.com/watch?v=Bd35Ze7-dIw)<br/>
* [제대로 파는 Git & GitHub 강좌](https://www.youtube.com/watch?v=1I3hMwQU6GU)
