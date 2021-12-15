# chearin.github.io
## 프로젝트 빌드 과정
1. github에 remote repository를 생성한다.
(이때 public해야한다.)
2. 내 컴퓨터 안에서 폴더를 생성한다.
3. 폴더와 github를 연동한다.
4. jekyll로 블로그를 생성한다.
(먼저 Ruby을 설치한다.)
(Ruby prompt로 jekyll의 기본 블로그를 위한 파일을 다운로드한다.)
5. 테마를 선택하고, 테마에 대한 전체 파일 clone해온다.
6. 기본 테마에 대한 파일들을 선택한 테마에 대한 파일들로 바꿔준다.
(_posts, README.md는 기존 파일을 유지한다.)
7. _config.yml 파일에 내용을 수정한다.
8. _posts폴더에 파일을 추가해서 post 항목들을 추가한다.
9. github에 파일들을 add, commit, push한다.
<br>

## 어려움
1. User 이름을 한글로 해놓아서 경로상에 한글이 들어갔다. 그래서 오류가 발생했다.
#### 해결: User 이름을 영어로 바꿔주었다.

2. jekyll 기본 블로그 파일을 다운로드하고 bundle exec jekyll serve 명령어로 열려고 하면 index.html 파일이 열렸다.
#### 해결: index.html 파일이 있어도 된다고 생각했는데 삭제해줘야 기본 블로그 파일이 열릴 수 있었다.
