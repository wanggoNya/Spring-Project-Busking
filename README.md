# Buskerz 스프링 프로젝트 By 일조가일냈조 
### 길거리의 아티스트와 시민을 연결짓는 버스킹 정보 공유 플랫폼
### Busking information sharing platform that connects street artists and citizens
#### Project nickname : 버스커즈
#### Project execution period : 2022.06.14~2022.07.01


## Description
버스커즈는 "길거리의 모든 춤과 음악, 그리고 예술"  누구나 아티스트가 되어 자신만의 버스킹을 홍보한다. 

* 일반 계정도 간단하게 아티스트 계정으로 등록하여 아티스트 정보 관리, 후원 내역을 관리할 수 있다. 
* 음악에 국한되었던 버스킹을 뮤지션, 퍼포먼스 카테고리로 나누어 버스킹의 영역을 확장시키고, <br> 취향에 맞는  다양한 버스킹을 찾을 수 있다.
* 아티스트는 손쉽게 자신의 버스킹 공연을 홍보하고, 사용자는 지역별 실시간 버스킹 공연을 검색할 수 있다.

## Environment

`IntelliJ` `DBeaver` `tomcat` `jdk 11`
  
## Tech stack
`JAVA` `Spring-Boot` `myBatis` `Hikari CP` `Oracle` `HTML/CSS` `JavaScript` `Jquery` `Thymeleaf` `Ajax`

<br> 

## 서비스 설명
### 서비스 기능 및 화면 리스트
![007](https://user-images.githubusercontent.com/96973332/179354669-37e87924-c036-48ac-927a-5410b0ff9f5b.png)
![008](https://user-images.githubusercontent.com/96973332/179354694-dbb3565b-bc98-45c7-badd-1c0cd18cba90.png)

### 메뉴트리
![011](https://user-images.githubusercontent.com/96973332/179354697-80cfccde-53d1-473e-baf7-f7939f98e897.png)
![013](https://user-images.githubusercontent.com/96973332/179354698-890a67eb-c958-4332-9d27-d4b41ba6b990.png)
![버스커즈_일조가일냈조-009](https://user-images.githubusercontent.com/96973332/179354789-8c2988c0-0100-4a05-af8e-5579359f33ac.png)

<br> 

## 🍊왕고냐가 구현한 기능
### 공연 예정 페이지 
`공연 댓글 순위` `신인 아티스트 목록` `공연 등록` `공연 수정/삭제` `공연 대표 포스터 이미지 등록/수정/삭제` <br>
`REST를 이용한 공연 페이징 처리` `REST를 이용한 공연 카테고리 분류` `디데이순 정렬의 공연 목록` <br>
`REST를 이용한 댓글 목록/등록/수정/삭제/페이징 처리` `공연 정보 유효성검사` `댓글 유효성 검사`

### 실시간 공연
`카카오맵API를 이용한 실시간 공연 안내` `모달창으로 실시간 공연 안내`

### 로그인
`아이디/비밀번호 유효성 검사` `카카오로그인API를 이용한 카카오 아이디 로그인` `일반 회원가입` `세션 등록/유지/삭제`

### 회원가입
`카카오로그인API를 이용한 카카오 계정 회원가입` `일반 회원가입` `아이디/휴대폰번호 중복검사`

### 아이디/비밀번호 찾기
`아이디/핸드폰 번호 조회` 

### 마이페이지
`페이지 이동 없이 마이페이지 메뉴 탭 구현`

<br> 

## 🍊왕고냐가 버스커즈 프로젝트로 느낀 점
### 에러 정리는 아주 중요하다. 
어제 본 에러가 오늘도 보이고, 방금 해결한 에러로 팀원도 고생할 확률이 높다. 에러 메세지와 해결원인, 해결법을 기록해두면 공부도 되거니와 프로젝트 진행률을 높이는데 기여할 수 있었다.👍

### 프로젝트를 진행하는데 있어, 팀원간의 코드리뷰와 서비스 흐름에 대한 토론은 필요하다. 
AJAX를 이용하여 페이지 이동 없는 화면을 구현할 때 팀원과 나의 DOM을 넣는 방식에 차이가 있었다. "이걸 이렇게도 할 수 있구나" 라는 생각은 더 나은, 더 효율적인 방법을 고안하게 만들었다. 생각하지 못했던 색다른 방법을 보면 사고의 확장이 일어나고 이 또한 학습의 원동력이 되었다.

### 데드라인을 지키기 위해서 개발 일지, 스케쥴러 작성은 아주 효과적이다. 
지난 프로젝트에서 기능 미구현이 있어 아쉬웠기 때문에, 이번 프로젝트에서는 모든 업무를 시작하기 전에 나에게 주어진 업무를 잘게 쪼개서 기록한 후 날짜별로 할당했다. 그리고 그 날마다 진행 상황을 파악하여 계획을 수정했고 프로젝트 마감까지 업무를 모두 끝마칠 수 있었다. 팀 프로젝트지만 개인의 할당량은 어느 누가 개입해서 도와주기 어렵기 때문에 각자가 일정을 잘 관리해야 한다. 난 이것을 슬랙(Slack)에 Todo List를 만들어 팀원에게 공유하고, 업무를 잘게 쪼개어 날짜마다 할당한 후 깃허브 리드미에 진행 현황을 올리는 방식을 통해 성공적으로 업무를 마칠 수 있었다.

### 팀 프로젝트의 핵심은 협업이다.
혼자서 진행하는 것이 아니라 팀원과 '협업'을 통해 이뤄내야하는 결과물이기에, 내가 좋은 팀원이 되어 좋은 성과물이 나올 수 있도록 팀에 기여하는 것이 중요했다. 기술적인 측면, 관계적인 측면에서 바라보면 깨달은 점은 이러하다.

* 기술적인 측면 <br>
프로젝트를 진행하다 보면 예상치 못한 난관은 꼭 존재한다. 내일까지 완료해야하는 기능에 에러가 있어 몇 시간동안 진전이 없다거나 하는 경우이다. 일정 시간 투자했을 때도 해결이 안 되면 팀원과 에러에 대한 의견을 공유하고, 여러 사람에게 해결방법을 묻고, 함께 해결해나가야 한다. <br>
내가 묻는 것도 중요했지만 반대로 누가 나에게 질문했을 때 '함께' 해결하는 것이 중요했다. 팀원이 질문했을 때 누구도 도와주지 않으면, 어느 한 부분의 완성이 지체되고 연쇄효과로 다른 부분까지 밀려났다. 이를 통해 배운 것은, 내 업무가 바쁘다고 팀원의 어려움을 무시하는 순간 팀 프로젝트가 아니게 된다는 것이다. 결국 함께 해결하고 함께 나아가야 했다. 이를 느낀 후에는 팀원이 어려움을 느낄 때 최대한 적극적으로 도와주려고 노력했고, 이로인해 프로젝트의 완성도를 높일 수 있었다.

* 관계적인 측면 <br>
각기 다른 7명의 사람이 모여 동일한 목표를 바라보기 때문에 의견 충돌과 갈등은 필히 존재할 수 밖에 없었다. 이를 해결하는 방법은 여러 가지가 있겠지만, 버스커즈 프로젝트를 하며 깨달은 것은 "갈등 상황에 대해 생각을 나누기" 이었다. 한 사람의 불만으로 프로젝트 진행에 어려움이 있을 뻔 했지만, 불만을 서로에게 솔직하게 공유했고 이를 다같이 피드백으로 받아들이는 노력을 했다. 갈등에도 항상 반성할 점과 배울 점이 있었고 이를 이용하면 더 나은 팀원, 더 나은 프로젝트 결과물이 나올 수 있다는 것을 알게 됐다.
