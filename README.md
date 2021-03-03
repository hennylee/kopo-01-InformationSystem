# [한국폴리텍대학/데이터 분석학과] 01_github강의 


# 1. 버전관리


## Repository란?

![image](https://user-images.githubusercontent.com/77392444/109835326-78423980-7c86-11eb-8824-2ea36c968692.png)

- Repository란 깃허브 내의 저장소를 의미합니다. 

- 깃허브에는 버전 관리를 하고 싶은 자료(코드 및 기타 요소)들이 저장되어 있는데, 각 코드를 폴더별로 관리하고 싶을 때 Repository를 사용합니다. 


## branch란?

![image](https://user-images.githubusercontent.com/77392444/109836920-ff43e180-7c87-11eb-9bab-970f80b2c56d.png)

- Branch란 하나의 폴더(Repository)를 용도에 따라 나눈 복사본이다.

- 각 브랜치에서의 작업은 기본적으로 동기화되지 않아, 서로 다른 작업을 수행할 수 있다.

- 각 브랜치에 commit된 내용은 다른 브랜치로 합칠 수 있는데, 이를 merge라고 한다. 

- 브랜치 관련 명령어는 다음과 같다.
  * 브랜치 만들기 : `git branch 새로운 브랜치명`

  * branch 이동하기 : `git checkout 이동할 브랜치명`

  * 다른 branch의 변경내역 합치기 : `git merge 병합할 브랜치명`

## commit이란?

- commit이란 Repository에 수정된 내용을 반영하는 과정이다. 

- 각 브랜치에 별도로 commit하면 해당 브랜치에만 반영된다.

- commit내역을 보면 Repository의 branch별로 수정된 과정을 확인할 수 있다. 

- 그래서 협업 시, 컨벤션에 맞는  commit message 작성하는 것이 중요하다.

- commit을 수행하기 전에는 반드시 `git add`하여 stash라는 임시저장소에 추가하는 과정을 거쳐야 한다.

- commit 관련 명령어
  * 임시저장소에 추가하기 : `git add 옮길 파일명.확장자` / `git add --all`
  * commit하기 : `git commit -m 커밋 메세지 내용`

