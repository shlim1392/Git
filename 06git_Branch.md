# Branch
>개발에서 메인 코드 베이스와는 독립적으로 새로운 기능이나 버그 수정을 안전하게 작업할 수 있는 분리된 작업환경 

### git branch {branch name}
> 브랜치 생성  
> git branch -v : 브랜치 확인(로컬)
> git branch -a : 리모트에 올라가있는 브랜치까지 확인
> git branch -D {branch name} : 브랜치 삭제

### git fetchad
> 브랜치 갱신
> git fetch --prune : 없어진 브랜치를 자동 삭제

**vscode extension > git graph 커밋그래프 확인가능**

## git pull {remote name} {branch}
>repository의 최신 변경사항들을 가져옴

