# Terms related to Git
* Git : Distributed Version Management System.
* Git Hub : Sites where you can upload projects that you manage with git.
* Local repository : It refers to a directory created by the git init command.
* Remote repository : Where to upload the local repository. GitHub.
* Working tree : Working Directory.   


# Upload to Git
You perform these tasks in the __local repository__.   

## 0. Git initial settings
You only have to do this once.
```
git config --global user.email [user email]
git config --global user.name "[user name]"
```
You have to do this when you init new reporitory.
```
git init
git remote add [repository nickname] [remote repository address]
```

## 1. Put on the stage
```
git add [file name]
```

## 2. Verified version
If you want to fix recent commit, use <code>--amend</code> option.
```
git commit -m "[content]"
git commit --amend -m "[content]"
```

## 3. From local, to remote
```
git push [repository nickname] [branch name]
```

## 4. From remote, to local
Synchronize changes to remote repositorie from local.
```
git pull [repository nickname] [branch name]
```
Replicate from remote repository (download).
```
git clone [remote repository address]
```

## 5. Confirm Proccess
```
git status
git log
```
