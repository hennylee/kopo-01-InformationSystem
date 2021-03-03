# [한국폴리텍대학/데이터 분석학과] 01_github강의 

## 1. 버전관리

- 협업 시, 컨벤션에 맞는  commit message 작성하는 것이 중요하다.

- 기능별로 branch 나눠서 버전 관리를 한다.

  - 각 브랜치에 별도로 commit하면 해당 브랜치에만 반영된다.

- [settings] - [github pages] 에서 손쉽게 웹사이트를 만들 수 있다.  

## 2. local git 설치

### 리눅스 명령어

* 폴더 접근하기 : `cd 폴더명`

* 폴더 뒤로가기 : `cd ..`

### Git 명령어

* 로그 확인 : `git log`

* 로그 상세 확인 : `git log -p`


#### branch

* 브랜치 만들기 : `git branch 새로운 브랜치명`

* 브랜치 바꾸기 : `git checkout 옮길 브랜치명`

  * 브랜치를 바꾼 뒤 commit하면, 해당 브랜치에서만 변경된 내용이 저장된다.


#### Merge 

* 변경내역 합칠 branch로 이동하기 : `git checkout 반영할 브랜치명`
* 다른 branch의 변경내역 합치기 : `git merge 병합할 브랜치명`
