# Github에 저장소 만들고 업로드하기
add -> commit -> push   
-------------------
## 1. Github 가입하기
## 2. Github에 저장소 만들기
git 저장소 이름 복사
## 3. 원격저장소를 컴퓨터로 가져오기
**git config --global user.name "깃허브 이름"**   
**git config --global user.email "이메일"**   
**git clone 복사한 저장소주소**   
명령어를 입력해주면 저장소 이름과 같은 폴더가 하나 생김   
폴더안으로 들어가서
## 4. 파일작업(생성,수정, 삭제 등) 후 스테이징 영역으로 이동시키기
**git status**   
->  현재 저장소의 팡리 상태를 한눈에 볼 수 있음   
방금 생성한 파일이 untracked files에 붉게 보임   
**git add * **   
-> untracked파일들이 모두 스테이징 영역으로 이동 됨
**git status**  
## 5. 스테이징 영역의 파일들을 커밋하기
**git commit -m "커밋메세지"**  
-> 커밋메세지에는 코드의 변경사항, 기능 추가 등 내용을 짧게 작성
## 6. 커밋한 내용 업로드
**git pull**  
-> 다른 사람이 PR을 통해서 코드를 업데이트 했거나, github을 통해서 commit했을 때
그 내용을 클라이언트로 내려받는 명령어   
**git push origin master**  
-> origin은 등록한 원격저장소, master는 브랜치이름   
= 원격저장소의 이름을 origin으로 등록한것이고   
해당저장소의 master브랜치로 push한다는 명령어   
## 7. 확인

## reference
+ https://codevkr.tistory.com/46
+ https://ngee.tistory.com/2185
