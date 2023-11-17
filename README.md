# Git Practice

git을 사용하는 연습을 해봅시다.


## Git 기본 명령어

기본. Git에 추가되지 않은 상태 | git add -> Git에 추가 준비 상태 | git commit -> Git에 추가된 상태


git add: 어떤 파일을 작업 이력으로 기록할 준비 (해당 파일들이 프로젝트에 추가될꺼야!)  
git commit: add된 파일들을 바탕으로 새로운 변경사항(작업)을 기록  
git log: commit한 기록들 확인 가능  
git log --oneline: 최신 커밋 기록 하나만 확인



------- github 올리 전까지 쓸 수 있는 명령어 ----------

git restore <파일명>: 변경 전 파일의 상태로 되돌릴 수 있다. (add에 올리기 전에 파일 상태를 되돌릴 수 있다.)  
git restore <파일명>: git add 하기 전 상태로 돌리는 명령어 (변경 상태 -> 원래 상태)  
git restore --staged <파일명>: add된 상태로 staging area에 업로도된 상태를 원복하라는 명령어 (add된 상태 -> add 전 상태)  
git reset <이동할 커밋ID>: 파일은 그대로 있으나 커밋은 사라짐, (별로 좋지 않는 명령어임, 커밋은 가능한 되돌리지 말기)


---------------- github 등록 -------------------

ssh-keygen  
cat .ssh/id_rsa.pub  <- 공개키 암호화 방식

```
git add
git commit
git push --set-upstream origin main
```


git remote set-url origin <주소>: remote origin 정보 수정  
git config --global init.defaultBranch main: 기본 브랜치 이름 변경


## github에서 추가한 내용
이제 pull을 연습해보자  
```
git pull
```
