# Initialize New Repository

```
$ git init

$ git remote add origin git@github.com:<user>/<repository>.git

$ git push -u origin master
```



# Take a Snapshot of teh contents of all files under the current directory

```
$ git add .
```



# Remove Snapshot of the file

```
$ git rm --cached <file path>
```



# Snapshot Scroll Back 

```
$ git reset HEAD
```

用版本库内容清空暂存区，git reset HEAD 回退到当前版本（在Git中，用HEAD表示当前版本，上一个版本就是HEAD^，上上一个版本就是HEAD^^，当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100）；

# Delete Local GitHub Repository

```
$ rm -rf <repo_folder>/.git
```



 git remote add origin https://github.com/ZikaiO/Notes.git



# 以下命令只clone master分支

```
$ git clone 
```



# Delete branch

```
$ git branch -d <local-branch>
```

If you want to delete such a branch nonetheless (e.g. because you've programmed yourself into a dead end and produced commits that aren't worth keeping) you can do so with the "-D" flag:

```
$ git branch -D <local-branch>
```

