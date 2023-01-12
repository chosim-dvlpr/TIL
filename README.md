# 2023.01.12

## Markdown

### Functions

1. 소제목 : #
2. 코드 블럭
   - 한 줄 : `abc`
   - 여러 줄 : ``` abc ```
3. 링크 : [string] (url)
4. 이미지 링크 : ! [string] (url)
5. 텍스트 강조
   - Bold : * * abc * *
   - Italic : * abc *
   - 취소선 : ~ ~ abc ~ ~
6. 구분선 : ---


---

## GUI vs CLI

- GUI : Graphic User Interface
  - 그래픽으로 사용자와 소통
  - 사용이 쉽지만 단계가 많고 컴퓨터의 성능을 더 많이 소모
  - 더블클릭, 드래그 등
- CLI : Command Line Interface
  - 명령어로 사용자와 소통

### CLI

- ls : 현재 경로의 파일 목록 확인
- clear : 화면 지우기
- mkdir : 디렉토리 만들기
  - mkdir 폴더명
- cd : 디렉토리 이동
  - cd 위치
  - cd .. : 상위폴더로 이동
- pwd : 현재 위치 출력
- find -name 폴더명 : 폴더 경로 출력

삭제

- rmdir : 디렉토리 삭제
  - rmdir 폴더명
  - 빈 폴더만 삭제
- rm -r 폴더명 : 하위폴더 포함하여 삭제
- rm -f 폴더명 : 파일 유무 상관없이 강제 삭제

절대경로 vs 상대경로
- 절대경로 : 루트 디렉토리부터 목적 지점까지의 모든 경로
- 상대경로 : 현재 작업하고 있는 디렉토리를 기준으로 계산된 경로
  - ./ : 현재 작업 중인 폴더
  - ../ : 현재 작업중인 폴더의 상위 폴더



---


## Github

### Repository

- Repository : 디렉토리 버전을 관리하는 저장소

### Git area

1. working directory : 작업 영역
2. staging area : commit 생성
3. repository : 만들어진 commit을 저장

| working directory | staging area | localrepo | repository |
| ------- | ----- | --- | --- |
| git add -> | git commit -> | git push ->  |


### Git 명령어

main

1. git add
   - git add 파일명
   - 스테이지로 올리기
2. git commit
   - git commit -m '내용'
   - commit 작성
3. git push
   - git push origin main
   - git push -u origin main (맨 처음 사용 시)
   - github에 업로드
  
기타

1. git status
   - 현재 상태 확인
2. git remote add origin 주소
   - 로컬과 온라인 연결
3. git remote -v
   - 연결 확인
4. git diff 파일명
   - 변경된 부분 확인
5. 스테이지에서 내리기
   - git restore --staged 파일명
6. commit 이력 확인
   - git log

에러 시
1. 실행 종료
   - q
   - ctrl + c
2. VIM 종료 : ESC -> :q!

### Github -> Local Clone

코드 변경사항까지 저장
- https 주소 복사 후
- git clone 주소

코드만 저장
- ZIP file 다운로드

