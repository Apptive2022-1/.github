# CONTRIBUTING.md
Issue 화면            |  Pull Request 화면
:--------------------:|:------------------:
![표시 위치](https://user-images.githubusercontent.com/51331195/156929682-66c7647c-666f-4652-bbae-3ef0f91ca9a8.png) | ![표시 위치](https://user-images.githubusercontent.com/51331195/156929788-9000a4a0-e102-4034-8dd2-d1ee9c8df373.png)


 이 문서에서는 동아리에서 권장하는 컨벤션 및 협업 가이드라인을 설명합니다.
 이 페이지에 대한 링크는 위와 같이 PR, Issue 화면에 자동으로 표시됩니다.
 
## 목차
1. [브랜치 관리 전략](#브랜치-관리-전략)
   1. [Github Flow](#github-flow)
   2. [Pull Request](#pull-request)
   3. [Commit](#commit)
2. [코드 리뷰](#코드-리뷰)  
3. [코딩 컨벤션](#코딩-컨벤션)  

## 브랜치 관리 전략
![Untitled (2)](https://user-images.githubusercontent.com/51331195/156833254-74e245b7-980d-4162-a6d6-eae32ea2860b.png)
 브랜치 관리 전략은 간단한 Github Flow를 따르고자 합니다.
 
### Github Flow
- **master**와 브랜치로 구성된다.
- **master**는 항상 배포가 가능한 안정된 상태여야 한다.
- 개발 작업은 항상 브랜치에서 이루어져야 한다.
- 버그 해결, 기능 개발 단위로 브랜치를 딴다.
- 브랜치 명은 현재 하고 있는 작업을 나타낸다.

### Pull Request
- PR 이전에 1차적으로 구동 테스트를 한다.
- PR은 버그 해결, 기능 조각 구현 등 작은 단위가 좋다.
- 무거운 기능 구현은 중간중간 PR을 올린다.
- PR 제목은 처리한 작업을 알 수 있도록 적는다.

### Commit
 : 커밋 메시지는 [AngularJS Git Commit Convention](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit#heading=h.uyo6cb12dt6w)을 기초로 합니다. 자세한 내용은 별도 문서를 참고해주세요.
 * 커밋은 시간 순서대로 쌓는다.
 * 커밋 제목은 히스토리로부터 변경 내역을 쉽게 알 수 있도록 적는다.
 * 서로 밀접한 연관 또는 종속성을 갖는 변경내역은 하나의 커밋으로 합친다.
 * 커밋 제목에는 반드시 접두사를 붙인다.

## 코드 리뷰

## 코딩 컨벤션
