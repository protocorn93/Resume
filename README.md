##  이동건

**2019년 8월 졸업 예정입니다.**

현재 iOS를 공부하며 블로그를 운영중입니다.

- blog
  - http://baked-corn.tistory.com
  - https://ehdrjsdlzzzz.github.io (기존의 티스토리에서 이전 중입니다.)
- [Github](https://github.com/ehdrjsdlzzzz)

---

#### 보유 기술

- 언어
  - Swift 중고급
  - iOS 중급
- 기타
  - Git 중급
- 경험한 것들
  - 백엔드
    - 서버 대한 기본적인 지식을 보유하고 있습니다. 
    - 개인 작품을 위한 API 서버를 구축하고 배포할 수 있습니다.
    - 주로 사용했던 프레임워크
      - Ruby on Rails

---

#### 학력

**경기대학교** : 2012.03 ~ 재학중 (2019.09 졸업 예정)

**컴퓨터과학과** : 프로그래밍 언어론, 운영체제, 데이터베이스, 네트워크, 자료구조 등 전공 과목 이수

---

#### 경력

**케어랩스 굿닥** : 2019.02.12 ~

---
#### 활동

- **2016.03**
  - 건축학과에서 컴퓨터과학과로 전과
- **2016.09 ~ 2016.12**
  -  수도권 연합 IT 동아리 SOPT - 안드로이드 파트 수료 (19기)
- **2017.03 ~ 2017.12**
  - 멋쟁이사자처럼 - 아주대학교 5기 (멘티) 활동
    - Ruby on Rails를 이용한 웹 프로그래밍 교육 수료
    - iOS 스터디 운영
- **2018.03 ~ 현재**
  - 멋쟁이사자처럼 - 아주대학교 6기 (멘토 및 운영진) 활동
    - 비전공자들에게 웹의 기초와 Ruby on Rails 기초 문법 강의
    - iOS 스터디 운영
- **2018.05.17**
  - 네이버 대학생 해커톤 핵데이 iOS 주제로 참가
    - Gesture Video
- **2018.09.01**
  - 커넥트 재단에서 운영하는 [부스트코스](https://www.edwith.org/boostcourse-ios) **에이스 과정 스터디 팀장**으로 수료
    - 우수 스터디 인터뷰 진행 ([참고자료](https://m.post.naver.com/viewer/postView.nhn?volumeNo=16674489&memberNo=34635212))

---

#### 외국어 및 자격증

- 외국어
  - 영어
    - 중상
    - 토익 910점 (2017.02.12 취득)
    - 공식 문서를 읽는 것에 큰 어려움을 느끼지 않습니다. 
- 자격증
  - 정보처리기사 (2018.05.25 취득)

---

#### 프로젝트

## GitBingo (깃빙고)

**1일 1커밋을 실천하려는 개발자들을 위한 어플리케이션**

[**앱스토어**](https://itunes.apple.com/kr/app/gitbingo/id1435428800?l=en&mt=8), [레포지터리](https://github.com/ehdrjsdlzzzz/GitBingo)



#### 기술

1. 실시간 Contribution 확인 가능
2. 원하는 시간에 알람을 받아 금일 커밋을 진행하였는지 확인 가능
3. 투데이 익스텐션 타겟을 사용해 위젯에서 이번주 커밋 정보와 알람 등록 시간을 확인 가능

#### 사용한 기술

- `Swift4`, `Xcode9`, `UserNotifications`, `Error Handling`, `Localizing`, `Networking`, `UIApplicationShortCuts`, `Today Extensions`, `SwiftLint`, `Unit Test`

#### 사용한 아키텍쳐

- `Delegation `, `Singleton`
- 시도한 아키텍쳐 : `MVP`

#### 공부한 내용 정리

- App Extension Programming Guide for iOS
  - [Essential](https://ehdrjsdlzzzz.github.io/2018/10/03/App-Extension-Programming-Guide-1/)
  - [Essential - Handling Common Scenarios](https://ehdrjsdlzzzz.github.io/2018/10/09/App-Extension-Programming-Guide-2/)

#### 사용한 라이브러리

- [`Kanna`](https://github.com/tid-kijyun/Kanna) - https://github.com/users/ehdrjsdlzzzz/contributions 로부터 HTML을 파싱해오기 위해 사용
- [`SVProgressHUD`](https://github.com/SVProgressHUD/SVProgressHUD) - Indicator와 함께 코멘트를 사용하기 위해 사용
- [`SwiftLint`](https://github.com/realm/SwiftLint) - Swift 스타일과 컨벤션을 지키기 위해

#### 문제점

- 웹 브라우저에선 00:00 이후 다음 날 컨트리뷰션 도트를 바로 확인 가능하지만 앱에선 GMT 시간 차로 오전 9시가 되어서야 그날의 도트를 받아올 수 있음.
  - 이 문제를 해결하기 위해 많은 노력을 해보았으나 해결하지 못함
  - 확인해본 결과 모바일 크롬이나 사파리에서도 동일한 이슈가 발생한 것으로 모바일에서 요청한 것에 대한 깃헙 서버의 응답에 이슈가 있는 것으로 판단하였음.

#### 스크린샷

**메인**

<img src="./images/Main.png" width="500">

**알람등록**

<img src="./images/Notification.png" width="600">

**알람**

<img src="./images/NotificationAlert.png" width="300">

**Version 2.0 - Widget** 

<img src="./images/Widget.png" width="200">
