# PracticeGitFlow

- Git Flow를 숙달해보고자 만든 레파지토리입니다.


## 커밋 순서

Main 브런치 - 배포용

1. Develop 브런치 생성 - 개발하는 브런치
2. Feature 브런치 생성 - 기능을 개발하는 브런치
	2.1 Git Convension
		- 협업자들과 원칙을 정해 commit message를 일관성 있게 작성합니다.
**sudden!** Feature 브랜치에서 merge하기 전에 다른 개발자가 develop에 기능을 추가함! -> 이 경우 merge를 하면서 Accept Both Change로 변경(VSCode 기준), commit!

3. 실수로 변경 저장하지 않고 feature 브랜치를 develop에 merge 했습니다. 그리고 변경완료한 것을 feature 브랜치에 commit 했습니다.

4. develop에 의미없는 commit을 한 후에 현재 feature를 devlope에 다시 merge 시도합니다.

5. 또다시 feature에서 merege한 내용이 develop에 반영이 안됨!

6. feature 브랜치에서 git merge develop이 아닌, develop 브랜치에서 git merge feature를 해야한다!