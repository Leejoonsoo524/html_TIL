# HTML
### 250804 HTML시작
* 비주얼 스튜디오 코드 설치, 깃허브 회원가입, 깃 설치
* 비주얼 스튜디오 환경설정 및 플러그인 설치
### 주의사항
1. 영문 대소문자 사용하기(소문자 권장) 예) subTitle, sub_title
2. 숫자는 영문 뒤로 배치하기 예) sub1, main002
3. 공백 + 한글 사용금지
4. 특수문자 사용금지(#,$,%,^,&,*,(,+,\,~,★ 등..) *언더바(`_`) 하이픈(`-`) 가능
5. 이름은 의미있게 사용하기 예) images, fonts, mail, cafe 등..
6. 비주얼 스튜디어코드 실행 시 작업 폴더 연결되어 있는지 확인하기
7. 작업폴더 연결이 안됐으면 -> File -> Close Folder 후 File -> Open Folder
### 깃(git) 설치 확인
* VScode 에서 단축키 'Ctrl + j' (터미널 실행)
* 터미널 실행 후 
* git-v (git 버전 확인 및 설치유무 확인)
### 터미널 기본설정
* 윈도우 기본 터미널 powershell을 git Bash 로 변경하기
* git Bash는 git 설치후 사용가능
## git 설정과 gitHub 업로드까지 순서 (터미널 입력 기준)
1. 'git config --list' : 현재 깃 설정 정보 확인
2. 새로운 입력창이 안뜰땐 터미널에서 'Ctrl+C' 또는 'Q' 입력
3. 위 설정 정보 확인시 내 정보가 아닐경우 
4. git config --global user.email "may2497@nate.com"
5. git config --global user.name "Leejoonsoo524"
6. 1번 명령어 다시 입력해서 확인
---
7. 'git init' : 현재 폴더를 작업 디렉터리 폴더로 연결, 폴더경로 옆에 **master** 표시 생기면 성공
8. 'git branch -M main' : 깃 디렉터리 명칭을 브랜치라 부름. 해당 브랜치명을 개인에 맞게 변경 기본이 **main**
---
9. 'git add .' **.** 이란 수정작업한 모든 파일을 올린다는뜻 'git add + 파일명' 해당 파일만 add 한다.
10. 'git status' : 현재 스테이지 확인 -> add 하기 전에 보통 확인하고 add 후에 다 올라갔는지 확인할수있다.
11. 'git commit -m "수정내용"' : 임시 저장소에 수정한 내용과 함께 수정된 내용을 저장한다.
12. 'git remote add origin https://github.com/Leejoonsoo524/html_TIL.git' : 깃허브 저장소 업로드 위치가 어디인지 주소연결
13. 'git push origin main' :  완전히 저장된 내용을 git 서버에 업로드 한다.