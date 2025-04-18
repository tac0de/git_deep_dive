04.17 (목) study2

1. git clone "리퍼지토리 URL" //github에서 갖고오기

2. git add . //전체 한꺼번에 add. commit의 전 단계. 커밋 하기전에 add를 해줘야 커밋 할 수 있음.

3. git commit -m "commit 메시지" //git에 저장

4. git reflog //히스토리 확인. git reset, git rebase 명령어로 삭제된 커밋을 포함한 모든 커밋 히스토리를 볼 수 있음.

5. git log //히스토리 확인. 커밋 기록을 모두 보여주는 명령어. 일반적.

6. git reset --soft HEAD~2 //HEAD (현재 내가 위치해있는 커밋을 가리키는 식별자). 현재 시점의 파일들을 그대로 보존하고 커밋만 과거로 돌릴 수 있음. 커밋ID에서  2만큼 떨어진 커밋ID로 변경하고, 이력은 완전히 지움.

7. git checkout -b feature/testfile //브랜치 생성

8. git branch //브랜치 생성 확인

9. git switch main //브랜치 전환. 오직 브랜치 전환.

10. git checkout main //브랜치 전환. 브랜치 전환, 파일 체크아웃, 커밋으로 돌아가기 등 다양한 용도로 사용.

11. git merge feature/testfile //master에서 feature/testfile 병합

12. git push origin main //push를 통해 gitgub에 최신을 올림.