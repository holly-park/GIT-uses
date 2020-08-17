많은 프로그래머들이 애플리케이션을 만드는 중, 에러가 뜨거나 궁금한 상황은 대부분 구글링을 통해서 해결할 것이다. 나도 마찬가지였다. 그 중 나는 tistroy, github 블로그가 구글의 첫 페이지에서 많이 보였다. (직접 .com도메인으로 운영하시는 분들도 다수 보았다.)

개인용으로 공부한 내용을 매일 기록하고 있는 naver블로그가 있었는데, 이제 commit관리를 하기 위해서 github블로그에 내가 공부한 내용을 정리하고자, 이렇게 깃헙 블로그를 개설하게 되었다.
<br>
## 순서


##### Github
###### 1.create repository
레퍼지토리 이름은 **username/github.io** 으로 commit한다.
###### 2.clone or download
clone or download라는 버튼을 눌러서 **Clone with https URL**을 복사해놓기
###### 3.구글에 **jekyll free theme** 검색
마음에 드는 블로그 테마 고르기
###### 4.code라는 버튼을 클릭
**download zip** 선택하여 다운로드
###### 5.zip파일을 압축 풀은 후 붙여넣기
나의 repositoy에 **Upload**
 <u>*주의: 압축을 풀은 폴더 자체를 올리지 말고 안에 들어있는 파일들을 업로드</u>
 <br>
 <br>

##### 블로그 포스트는 마크다운 형식이기 때문에, 마크다운을 문서를 쉽게 작성하기 위한 Atom 에디터를 설치한다. Atom은 git과의 연결도 쉽다.
만약 git을 깔지 않으셨다면 git도 다운로드 한다
<br>
<br>

##### [download 및 install]
[git download](https://git-scm.com/downloads)<br>
[atom download](https://atom.io/)

<br><br>
##### [내 컴퓨터 local에 git을 위한 새로운 폴더 생성]
1.내가 편한 경로에 새로운 폴더를 생성하기 (폴더A)
2.새로운 폴더안에 '커밋 및 푸쉬'를 위한 새로운 폴더(폴더A-1)
<br>
<br>

##### [cmd창]
```
1.cd (폴더A-1의 경로)
2.뒤의 명령어들을 한 줄씩 입력
3.git init
4.git config user.name (깃 username입력)
5.git config user.email (깃 email입력)
6.git remote add origin (첫번째 스텝에서 복사한 clone with https URL 붙여넣기)
7.git pull (방금전 붙여넣기한 URL 다시 붙여넣기)
```
*추후 레포지토리에서 수정을 한 경우, 7번 순서만 다시 update해주면 수정 내용이 로컬에 반영된다.
<br>
<br>

##### [atom과 git연동]
1.atom에디터에서 open folder를 눌러서 폴더 **A-1** 열기
<br>
2.setting파일 열기 **[ctrl + ,]**-[install]-**[markdown-preview-enhanced** 검색 및 설치] -기본 미리보기 에디터[markdown preview] 비활성화
3.수정하고 싶은 파일 수정(미리보기: **ctrl + shift + m**)

<br>
<br>
##### [atom 에디터에서 변경사항 저장 및 마무리]
[view]-[Toggle Git tab]-[Stage All]-[메세지작성: hello atom-git 폴더1-1]-[create detached commit]-[Publish]
