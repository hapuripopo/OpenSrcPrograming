# Terms related to Git
* Git : 분산 버전 관리 시스템
* Git Hub : 깃으로 관리하는 프로젝트를 올려 둘 수 있는 사이트
* Local Repository : git init 명령어로 생성되는 디렉토리를 말한다.
* Remote Repository : 로컬 저장소를 upload하는 곳. GitHub.
* Working Tree : 작업 디렉토리


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

## 5. Confirm Proccess
```
git status
git log
```
