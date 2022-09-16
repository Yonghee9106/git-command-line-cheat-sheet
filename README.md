# Table of Contents

* [Git Version Check](#Git-Version-Check)
* [Git Initialization](#Git-Initialization)
* [Git Configuration](#Git-Configuration)
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

The `git config` is used to set the configuration values on a local, global or system level.
<br/><br/>

Let's change the email address to email@<span></span>gamil.com on a global level.
```git
$ git config --global user.email "email@gamil.com"
```



<br/><br/>



## References

### Cheat Sheet
* [Atlassian Git Cheat Sheet](https://github.com/Yonghee9106/git-study-history/files/9484490/SWTM-2088_Atlassian-Git-Cheatsheet.pdf)

### Youtube
* [깃, 깃허브 이건 알고 사용하자](https://www.youtube.com/watch?v=lPrxhA4PLoA)<br/>
* [Git은 뭐고 Github은 뭔가요?](https://www.youtube.com/watch?v=Bd35Ze7-dIw)<br/>
* [제대로 파는 Git & GitHub 강좌](https://www.youtube.com/watch?v=1I3hMwQU6GU)
