# git_command
깃 명령어 모음

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