## WELCOME TO TEAM 147B

HOMEPAGE OF THE TEAM 147B

### TEAM NAME

147B

```markdown
- Student Name
1. Cho Jun Ho
2. Lee Dong Young
3. Park Bo Gyu
```

### Project URL

PIKE Programming Language : https://github.com/17-1-SKKU-OSS/Pike.git

# 활동내역 및 기타사항

### Our Project : PIKE Language
(1) PIKE 언어를 학습해보자.
- C언어와는 어떠한 차이점이 존재할까?
- C언어와의 효율성을 비교해보자. 어떤점이 효율적이고 어떤점이 비효율적인가.

(2) PIKE 공식 홈페이지를 탐구해보자.
- 홈페이지에 오탈자가 존재하는가?
- 홈페이지 사용에 대한 애로사항에는 어떠한 것이 있을까?

(3) PIKE Github를 탐구해보자.
- Github에 오탈자가 존재하는가?
- 그간 어떠한 버그가 존재했고, 교정되었는가?

*** 우리는 PIKE를 배우는 Beginner의 입장으로써 앞으로 PIKE가 초보자들에게 다가가기 위해서 어떠한 것이 추가되어야 할지에 대해서 논의할 예정입니다. ***

### 팀원별 역할과 활동
(1) 조준호 : Fork, Pull Request, Coding, Search Bug history

(2) 박보규 : Coding, Search Bug History

(3) 이동영 : 활동내역 정리, Search Bug History

### 활동내역 1
(1) 오늘 수행한 내용
- PIKE 기초 문법에 대해 학습 : string 변수 선언, 조건문, do ~ while 반복문, 함수호출

(2) 학습과정에서 어떠한 문제가 있었는가?
- main 함수 인자에 void 지원하지 않음
- 그래픽 UI, HTTP 모듈 등 다양한 모듈을 지원하나, 모듈 설치에 문제가 있어 오늘 수행하지 못함 (다음 학습 때 진행할 예정)
- sizeof(string value) == 0 의 조건을 만족하는 Case를 발견하지 못함
- PIKE 공식 홈페이지의 PIKE 사용설명서의 문단이 왼쪽으로 쏠려있어 홈페이지를 사용하는데 가독성이 상당히 떨어짐
- gtk PIKE module (그래픽 UI를 제공하기 위한 모듈)의 설치 바법이 상세하지 못하여 학습이 지연됨

### 활동내역 2
(1) 오늘 수행한 내용
- STL과 유사한 기능 학습
- PULL REQUEST 발송
We sent Pull Request 1 : difficult things as beginners.
++++++
- Because PIKE manual is tilted to the left, uncomfortable to read.
(PIKE 메뉴얼이 전체적으로 왼쪽으로 쏠려 있어, 읽기가 매우 불편합니다.)
- We don't know how to install and how to use gtk PIKE module and protocols.HTTP. We hope more detailed manual.
(gtk PIK 모듈이나 프로토콜.HTTP 를 어떻게 설치하고 사용하는지 상세 설명이 없어 학습에 불편합니다.)

### 활동내역 3
(1) 오늘 수행한 내용
- PULL REQUEST 에 대한 답변 회신
1. this should not be a pull-request but at an issue though even better would be to ask your questions on the mailinglist. there people will be happy to help you: http://pike.lysator.liu.se/forums/
(Pull-request 가 아닌 이슈를 활용할 것을 권고받았습니다. 학습에 포럼을 활용할 것을 권고받았습니다.)
2. FYI: There's been a new version of the tutorial lying around since I re-made the Pike site a couple of months ago, but it never got installed on the production server. On the occasion of this pull request we'll make that happen asap so that the tutorial on the Pike site is usable.
(새로운 튜토리얼을 만들었으나 아직 적용되지 않았다는 답변이 왔습니다. 이와 같은 요청이 누적될 경우 가능한 빨리 사용할 수 있도록 설정할 것이라는 긍정적 답변이었습니다.)
- 캐치와 게이지 문법을 학습
- 학습 상 어려운 점을 포럼에 등록된 메일로 발송 (이전 PULL REQUEST에 대한 답변에 의거)
- PIKE 홈페이지의 왼쪽 쏠림현상을 수정하기 위해 HTML 소스 수정 시도

### 반려당한 풀리퀘스트에 추가 코멘트가 등재되었습니다. (2017.06.13) ###
1. The introduction is still unreadable (unless you plan to do it on a 2001 flip mobile). Any progress on that?
(설명서가 여전히 읽을 수 없다는 유사 문의가 코멘트로 등재되었습니다.)
2. We are working on the new solution, which is partly implemented on the Pike site server, but we ran into some minor oddities we need to sort out before it is working properly. But it's in the making...
(번역: 우리는 부분적으로 파이크 사이트 서버에 구현 된 새로운 솔루션을 개발 중입니다. 하지만 제대로 작동하기 전에 미리 정렬해야하는 몇 가지 사소한 문제가 있으나 일단은 제작 중입니다 ...)
