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


