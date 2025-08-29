# GIT BASIC COMMAND

### 1. git init : git project로 세팅
```
$ git init
Initialized empty Git repository in ...(경로)
```
### 2. git status :파일 변경사항 등 상태보기


### 3. git add :특정 파일을 변경사항 기록 대기 상태로 변경
```
git add basic_command.md 

$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   basic_command.md
```
### 4. git commit : 기록 대기 상태에 있는 파일들을 기록

```
$ git commit -m "1st commit"
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   basic_command.md
```
