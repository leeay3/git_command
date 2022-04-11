# git_command
깃 명령어 모음

## 명령어
### git init
- 새 저장소(repository)를 만들고 난 후 깃을 시작하기 위한 명령어
- 프로젝트 폴더 내에 숨겨진 .git 디렉토리를 생성하고, Git은 현재 저장소에 대한 모든 변경사항을 추적 및 관리하게 된다.

### git status
- repository의 현재 상태를 확인할 수 있는 명령어
- Git으로 관리(추적)되고 있지 않던 파일이 있다면 해당 파일들을 staging area로 추가해줄 수 있다.
- 모든 변경사항을 확인할 수 있고, commit을 남기기 위해 staging area로 추가해줘야 한다.

### git add
- 원하는 파일들을 staging area로 추가해주는 명령어
- 여러개의 파일들을 추가하고 심다면
  ```<git add file.py file2.py file3.py>```
- ```git add .``` 는 프로젝트 폴더 내의 모든 파일과 폴더를 staging area에 추가하고 commit을 남길 수 있게 해준다.

### git commit -m "Commit message"
- 커밋 메시지를 남기는 명령어
- 식별을 위해 큰 따옴표 안에 커밋 메시지를 작성한다.

### git log
- 프로젝트의 모든 커밋 내용을 확인하는 명령어
- 작성자, hash 값, 날짜와 시간, 커밋 메시지의 정보를 확인할 수 있다.
- 특정 커밋 시점의 코드로 되돌리고 싶다면 ```git checkout <commit-hash>``` (```<commit-hash>``` 를 git log에서 보이는 commit의 실제 hash 값으로 변경해주면 된다.)
  
### git branch <new-branch-name>
- 새로운 브랜치를 생성하는 명령어
  
### git checkout <branch-name>
- 다른 브랜치로 이동하는 명령어

### git checkout -b <new-branch-name>
- 브랜치 생성과 동시에 생성된 브랜치로 바로 이동하는 명령어

### git branch
- 프로젝트에 존재하는 모든 브랜치를 확인하는 명령어

### git merge <branch-name>
- 현재 브랜치와 다른 브랜치를 병합하는 명령어

### git branch -d <branch-name>
- 브랜치 삭제하는 명령어

### git push origin master(or main)
- 로컬 repo를 Github repo로 push하는 명령어

### git pull origin master(or main)
- 로컬 repo Github에 있는 master(or main)과 서로 다른 내용을 가지고 있다면 ```<git pull>``` 을 사용하여 remote의 최신화된 코드를 내 로컬 repo에 반영하는 명령어