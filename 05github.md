# Github

## 1. SSH 생성
### ssh-keygen -t ed25519 -c "email"  
> ed25519 알고리즘으로 ssh 생성  
> github - setting - ssh and gpg keys에 등록

## 2. git config
### 사용자 설정
>git config user.name  
>git config user.email

## 3. git remote

### git remote add {remote name} {remote url}
> 깃허브 repository에 로컬 워크스페이스 연결   
> git remote -v : 어디에 연결되어있는지 확인  
> git remote remove {remote name} : 연결 삭제  

## 4. git push

### git branch -v
> 현재 브랜치 확인

### git push {remote name} {branch}

## 5. git clone {url}
>repository를 로컬에 복사

