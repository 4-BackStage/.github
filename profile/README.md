<h1 align="center">🎤 VYBZ 🎤</h1>

<p align="center">
  <i>팬과 버스커가 함께 만드는 무대, 실시간 소통 기반 팬 플랫폼 SNS</i>
</p>

<br/>

<table align="center">
  <tr>
    <td align="center">
      <img width="200" alt="스크린샷1" src="https://github.com/user-attachments/assets/260c1396-290c-4f57-b6e0-7d5048efb193">
    </td>
    <td align="center">
      <img width="600" alt="스크린샷2" src="https://github.com/user-attachments/assets/c0191e9d-73dc-4866-813d-687da167fc63">
    </td>
  </tr>
</table>



## 소개 및 개요

- 프로젝트 기간 : 2025.05.02. ~ 2025.07.15.
- 배포 URL(User) : [🔗 VYBZ](https://vybz.kr/)
- 배포 URL(Busker) : [🔗 VYBZ](https://busker.vybz.kr/)

### [프로젝트 설명]
* 버스킹 프로그램으로 인한 버스킹 문화에 대한 관심 증가
* 버스킹 공연 홍보 공간의 부재 / 버스킹 홍보
* 이러한 문제점들을 해결하기 위한 생태계를 만들기 위해 VYBZ 프로젝트를 시작했습니다.

### [아키텍처]
* MSA / EDA / CQRS / CDC
* 서비스 확장성과 안정적인 운영을 위한 구조적 선택
* 이벤트 중심 비동기 아키텍처
* 읽기와 쓰기를 분리한 효율적인 데이터 처리 구조

### [CI/CD 아키텍처]
<img width="638" height="456" alt="스크린샷 2025-07-11 오전 10 32 11" src="https://github.com/user-attachments/assets/eb18a78c-6256-4362-9d19-32aacc3dece1" />

### [System 아키텍처]
<img width="1002" height="430" alt="스크린샷 2025-07-11 오전 10 33 36" src="https://github.com/user-attachments/assets/b47a7f41-55a8-41f9-bd6e-8334a53a0a4a" />

### [MSA]
<img width="900" height="407" alt="스크린샷 2025-07-11 오전 10 34 59" src="https://github.com/user-attachments/assets/91c22bf1-3f03-473c-a344-61f5fd0c02ac" />

### [EDA]
<img width="916" height="367" alt="스크린샷 2025-07-11 오전 10 35 57" src="https://github.com/user-attachments/assets/aff2efe0-9cfb-48d1-a3fc-00a68458a29d" />

### [CQRS]
<img width="897" height="379" alt="스크린샷 2025-07-11 오전 10 36 32" src="https://github.com/user-attachments/assets/9cb438f1-c6ed-47fe-a6af-5b9c9657d79f" />

<br/>

<details>
<summary><h1>서비스별 repository 바로가기</h1></summary>
<div markdown="1">

라이브 서비스 ([`vybz-live`](https://github.com/2-BackStage/vybz-live)) <br>
라이브 채팅 서비스 ([`vybz-live-chat`](https://github.com/4-BackStage/vybz-live-chat)) <br>
채팅 서비스 ([`vybz-chat`](https://github.com/4-BackStage/vybz-chat)) <br>
피드 서비스 ([`vybz-feed`](https://github.com/4-BackStage/vybz-feed)) <br>
피드 read 서비스 ([`vybz-feed-read`](https://github.com/4-BackStage/vybz-feed-read)) <br>
집계 서비스 ([`vybz-aggregation`](https://github.com/4-BackStage/vybz-aggregation)) <br>
알림 서비스 ([`vybz-notification`](https://github.com/4-BackStage/vybz-notification)) <br>
팔로우 서비스 ([`vybz-follow`](https://github.com/4-BackStage/vybz-follow)) <br>
유저 정보 서비스 ([`vybz-user-info`](https://github.com/4-BackStage/vybz-user-info)) <br>
유저 정보 read 서비스 ([`vybz-user-info-read`](https://github.com/4-BackStage/vybz-user-info-read)) <br>
버스커 정보 서비스 ([`vybz-busker-info`](https://github.com/4-BackStage/vybz-busker-info)) <br>
버스커 정보 read 서비스 ([`vybz-busker-info-read`](https://github.com/4-BackStage/vybz-busker-info-read))  <br>
관리자 서비스 ([`vybz-admin`](https://github.com/4-BackStage/vybz-admin))  <br>
약관 서비스 ([`vybz-agreement`](https://github.com/4-BackStage/vybz-agreement))  <br>
버스커 계정 서비스 ([`vybz-auth-busker`](https://github.com/4-BackStage/vybz-auth-busker))  <br>
유저 계정 서비스 ([`vybz-auth-user`](https://github.com/4-BackStage/vybz-auth-user))  <br>
후원/멤버십/정산 서비스 ([`vybz-support`](https://github.com/4-BackStage/vybz-support))  <br>
결제 서비스 ([`vybz-payment`](https://github.com/4-BackStage/vybz-payment))  <br>
댓글 서비스 ([`vybz-comment`](https://github.com/4-BackStage/vybz-comment))  <br>
댓글 read 서비스 ([`vybz-comment-read`](https://github.com/4-BackStage/vybz-comment-read))  <br>
좋아요 서비스 ([`vybz-like`](https://github.com/4-BackStage/vybz-like))  <br>
검색 서비스 ([`vybz-search`](https://github.com/4-BackStage/vybz-search))  <br>
gateway ([`vybz-gateway`](https://github.com/4-BackStage/vybz-gateway))  <br>
eureka ([`vybz-eureka`](https://github.com/4-BackStage/vybz-eureka))  <br>

</div>
</details>

<br>

<details>
<summary><h1>목차</h1></summary>
<div markdown="1">

1. [팀 소개](#teamintro)
2. [기술 및 개발 환경](#stack)
3. [개발 기간 및 작업 문화](#task)
4. [주요 기능](#mainfeat)
5. [UI](#ui)
6. [역할분담](#role)
7. [느낀점](#impression)
</div>
</details>
<br/>

## <span id="teamintro">1. 팀 소개</span>
### 🚀 BackStage 팀을 소개합니다!
안녕하세요, 저희는 1명의 Front-end, 3명의 Back-end 개발자로 구성된 **BackStage**팀입니다. </br>
버스커들을 뒤에서 받쳐주는 든든한 지원군! 🎤
</br>
(신세계 스파로스 아카데미 6기 2차 2조 입니다.)


|                                                                   **✨ 김동현**                                                                   |                                                                  **✨ 최지호**                                                                   |                                                                    **✨ 조현재**                                                                     |                                                              **✨ 진성오**                                                              |
| :-----------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------: |
|                               <img src="https://github.com/user-attachments/assets/73561e3f-7a4a-4c16-82ff-17f85931e277" height=210 width=180>                               |     <img src="https://github.com/user-attachments/assets/bcac133d-ac50-44f8-8300-d5f3b088482c" height=210 width=180>      |       <img src="https://github.com/user-attachments/assets/2a8d8b2e-e0ec-42f8-96fe-c2ba36698b61" height=210 width=180>        | <img src="https://github.com/user-attachments/assets/f17f0b95-9d5d-4d7d-ab59-217cad3e258e" height=210 width=180> |
|                 **github**: [Demopeu](https://github.com/Demopeu)                 |      **github**: [jijihorang](https://github.com/jijihorang)       |                 **github**: [HyeonProG](https://github.com/HyeonProG)                  |       **github**: [jin-sung-oh](https://github.com/jin-sung-oh)        |
| ![FrontEnd](https://img.shields.io/badge/FrontEnd-3f97fb) <br> ![Team%20Leader](https://img.shields.io/badge/-Team%20leader-yellow) | ![BackEnd](https://img.shields.io/badge/BackEnd-000000) | ![BackEnd](https://img.shields.io/badge/BackEnd-000000) | ![BackEnd](https://img.shields.io/badge/BackEnd-000000) |


<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="stack">2. 기술 및 개발 환경</span>
### [사용 기술]
- Front-end <br><img src="https://img.shields.io/badge/turborepo-FF1E56?style=flat-square&logo=turborepo&logoColor=white"> <img src="https://img.shields.io/badge/next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"><img src="https://img.shields.io/badge/typescript-3178C6?style=flat-square&logo=nextdotjs&logoColor=white"> <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"> <img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcn/ui&logoColor=white"> <img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=PWA&logoColor=white">
<img src="https://img.shields.io/badge/FCM-DD2C00?style=flat-square&logo=firebase&logoColor=white"> <img src="https://img.shields.io/badge/Next Auth-000000?style=flat-square&logo=Next.js&logoColor=white"> <img src="https://img.shields.io/badge/tanstack query-DD2C00?style=flat-square&logo=&logoColor=white">

- Back-end <br>  <img src="https://img.shields.io/badge/java-%23ED8B00?style=flat-square&logo=openJDK&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat-square&logo=SpringSecurity&logoColor=white"> <img src="https://img.shields.io/badge/Json Web Tokens-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"> <img src="https://img.shields.io/badge/Spring Cloud-6DB33F?style=flat-square&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/Spring Eureka-6DB33F?style=flat-square&logo=Netflix&logoColor=white"> <img src="https://img.shields.io/badge/Spring Batch-6DB33F?style=flat-square&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/Spring WebFlux-6DB33F?style=flat-square&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/Apache Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"> <img src="https://img.shields.io/badge/Server Sent Event-3B66BC?style=flat-square&logo=&logoColor=white"> <img src="https://img.shields.io/badge/elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white"> <img src="https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=Kibana&logoColor=white"> <img src="https://img.shields.io/badge/WebSocket-000000?style=flat-square&logo=&logoColor=white"> <img src="https://img.shields.io/badge/Stomp-000000?style=flat-square&logo=&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/mongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"> <img src="https://img.shields.io/badge/redis-FF4438?style=flat-square&logo=redis&logoColor=white">

-  Infra <br> <img src="https://img.shields.io/badge/Amazon Ec2-FF9900?style=flat-square&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat-square&logoColor=white"> <img src="https://img.shields.io/badge/Github Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/NginX-009639?style=flat-square&logo=nginx&logoColor=white">
<br/>

### [개발 환경]
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=Discord&logoColor=white"/> <img src="https://img.shields.io/badge/KakaoTalk-FFCD00?style=flat-square&logo=kakaotalk&logoColor=white"/> 
- [Notion](https://www.notion.so/Back-Stage-1e59f61cd9ee80a9b845d7f307626891) : 진행 상황 및 회의, 전반적인 일정관리 회고록 등을 노션을 활용해서 진행했습니다.
- [Figma](https://www.figma.com/board/GLzu2vSwdha9Gd5lM3IWfh/2%EC%B0%A8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-Back-Stage-Event-Storming?node-id=0-1&t=to7B0Rotl1GPH5Hf-1) : 동시 접속하여 함께 이벤트 스토밍을 진행했습니다.
- [Figma](https://www.figma.com/design/XHHT05EyfuVoMBkEvdtHqg/Back-Stage-%ED%99%94%EB%A9%B4-%EC%84%A4%EA%B3%84?node-id=0-1&t=yB8M4TwAogC4fD5m-1) : 동시 접속하여 함께 화면 설계를 진행했습니다.
- `Kakao Talk` : 카카오톡을 통해 원활한 소통을 진행하였습니다.
- `Discord` : 디스코드를 통해 배포 성공, 실패 여부를 확인할 수 있도록 활용했습니다.
<br/>

### [IDE 및 테스트]
<img src="https://img.shields.io/badge/IntelliJ-000000?style=flat-square&logo=intellijidea&logoColor=white"/> <img src="https://img.shields.io/badge/Visual Studio Code-40AEF0?style=flat-square&logoColor=white"/> <img src="https://img.shields.io/badge/PostMan-FF6C37?style=flat-square&logo=postman&logoColor=white"/> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=white"/>
- `IntelliJ` : IntelliJ를 활용하여 백엔드 작업을 진행했습니다.
- `Visual Studio Code` : Visual Studio Code를 활용하여 프론트엔드 작업을 진행했습니다.
- `PostMan`, `Swagger` : PostMan 과 Swagger를 활용하여 api 통신 테스트 및 문서화 작업을 진행했습니다.

 ### [Git 흐름 전략]
각각의 기능을 담당하여 프로젝트를 진행하고자 [ Git Flow 방식 ] 을 사용했습니다.
페이지 별/ 기능 별 브랜치를 만들고 각자 작업 브랜치를 따로 생성하여, PR 및 Merge를 진행합니다.
<br/>
<br/>

 ### [커밋 컨벤션]
 [🔗 커밋 컨벤션 ](https://www.notion.so/git-conventions-1e59f61cd9ee81d79c41c7c6a425dae7)
 
```
- feat: 새로운 기능 구현
- fix: 오류 수정
- docs: 문서 수정 (예 : readme.md, json 파일 등 수정/ 문서 관련 라이브러리 설치 등)
- design: 마크업 및 style 작업
- style: 코드에 변화가 없는 수정 (예 : prettier, 세미콜론 등)
- refactor: 코드 리팩토링
- comment: 주석 추가
- chore: 빌드 부분 혹은 패키지 매니저 수정사항
- rename: 파일 혹은 폴더명 수정 or 옮기기
- remove: 파일 삭제
```
<br/>

 ### [코드 컨벤션]
 통일성 있는 코드 작성을 위해 다양한 [🔗 백엔드 코드 컨벤션 ](https://www.notion.so/Back-End-conventions-1e59f61cd9ee8102a66ac9272c6fdeb8), [🔗 프론트엔드 코드 컨벤션 ](https://www.notion.so/Front-End-conventions-1e59f61cd9ee81e5b820c1500d6fadc1)을 정해 사용했습니다.
 
 <br/>
 <p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id='task'>3. 개발 기간 및 작업 문화 </span>
### [프로젝트 기간] : 2025.05.02. ~ 2025.07.15.
### 작업물 관리

#### 📍 Google Docs
 프로젝트의 전반적인 내용과 작업 과정등을 google docs에 담아서 관리했습니다.
 [🔗 Google Docs](https://github.com/user-attachments/files/19932522/6.1.4.pdf)
 <br/>

#### 📍 Notion 회고
- 팀 노션에 동시 접속하여 [🔗 일일 회고](https://www.notion.so/1e59f61cd9ee81c9bef8f4694bc5a484)를 진행하고 진행사항을 파악했습니다.

<img width="600" alt="front" src="https://github.com/user-attachments/assets/780bd714-07f6-4e7d-a914-4c7b9f7290da">
<br/>

<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id='mainfeat'>4. 주요 기능</span>
### 🔒 사용자
 * 소셜 로그인(google, kakao)
 * 유효성 검사
 * 토큰 검증
### 🔒 버스커
 * 로그인
 * 회원가입
 * 유효성 검사
 * 토큰 검증
### 🎤 라이브
* 버스커 라이브 시작
* 버스커 라이브 종료
* 라이브 채팅
* 사용자 라이브 시청
<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/41fee8a8-de6e-41cb-a9de-1dd961405187" width="500"/>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/89db9675-67fc-4c13-af44-0316fe668f04" width="300"/>
    </td>
  </tr>
</table>


### 💬 1:1 채팅
* 채팅 방 생성
* 채팅 보내기
* 채팅 방 나가기
* SSE 요청
* 채팅 리스트 무한 스크롤
<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/a27ba7af-475b-4232-abc1-f37d7f20d57d" width="300"/>
    </td>
  </tr>
</table>


### 💳 결제/정기결제
* Toss Payments
* 단일 결제
* 정기 결제
<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/25e2e49d-4353-4661-961f-3ff5c0f6ccf8" width="300"/>
    </td>
  </tr>
</table>


<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="ui">5. UI</span>
<img width="450" alt="ui" src="https://github.com/user-attachments/assets/b1c14c06-8532-4034-99b8-e777c14e19f3">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/17f9d4b6-6c79-4011-86c7-0dce0e0e2ec6">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/3fb77057-add9-4fa4-b459-efbe4477a231">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/cc246b4c-7ab7-42cb-a7b5-4a6b327ee2ea">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/be988f68-3b4f-480d-b36e-e2cb64fa4786">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/091e42e9-f2ea-4055-bf23-91b7ee45188a">

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="role">6. 역할 분담</span>
<img width="800" alt="front" src="https://github.com/user-attachments/assets/a323315a-507c-4646-a8df-2ba61b94ac77">

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>


## <span id="impression">7. 느낀 점</span>

### 🐶 동현 


### 🐰 지호 
이번 VYBZ 프로젝트를 통해 처음으로 CI/CD를 담당하게 되었으며, GitHub Actions, Docker, EC2 등을 연동하는 과정을 처음부터 직접 구성해보았다. 익숙하지 않아 시행착오도 많았고, 자동화가 생각처럼 매끄럽게 되지 않아 답답했던 순간도 있었지만, 하나씩 해결해 나가며 동작하는 과정을 눈으로 확인했을 때 큰 보람을 느꼈습니다.

이번 프로젝트는 기술적으로도 도전이었지만, 낯선 영역에 스스로를 던지고 부딪혀보는 경험이 무엇보다 값졌다고 느꼈고, 앞으로도 이런 과정을 두려워하지 않고 계속 도전해나가고 싶다는 생각을 하게 되었습니다.

### 🐹 현재 
이번 VYBZ 프로젝트는 단순한 기능 구현을 넘어서 MSA 아키텍처 기반의 대규모 분산 시스템을 직접 설계하고 구축해본 첫 경험이었습니다.
Kafka 기반의 이벤트 중심 아키텍처(EDA), CQRS를 통한 읽기/쓰기 분리, MongoDB를 활용한 집계 및 실시간 채팅 등, 이론으로만 접하던 기술들을 실무에 가까운 수준으로 적용해보면서 큰 성장의 기회가 되었습니다.

특히 1:1 채팅 서비스를 구현하면서 구현가능한 여러 방면을 생각하고 비교해가며 기술을 선택해 보는 좋은 경험을 했습니다.

단순히 돌아가는 서비스가 아닌, 유지보수성과 확장성, 성능까지 고려된 백엔드 아키텍처를 고민하고 구현한 시간이었습니다.
이 프로젝트를 통해 한층 더 도전적인 개발자로 성장할 수 있었고, 앞으로도 문제 해결 중심의 기술적 접근을 이어가고 싶습니다.


### 🦁 성오 
이번 프로젝트는 실서비스 수준의 아키텍처 설계와 구현을 목표로 진행되었습니다. MSA 구조, Kafka 기반 비동기 이벤트 처리,CQRS,MongoDB 커서 기반 무한스크롤 등 다양한 기술을 처음부터 끝까지 직접 적용하며 많은 시행착오를 겪었고, 그 과정에서 서비스 설계와 안정성의 중요성을 깊이 이해하게 되었습니다.

특히 장애 상황에서 로그 분석을 통해 원인을 파악하고 팀원과 함께 문제를 해결한 경험은 큰 자신감으로 이어졌습니다. 협업 과정에서는 Git/GitHub 기반의 코드 리뷰, 컨벤션 통일, 이슈 관리 등을 통해 팀 개발 문화를 익혔고, 앞으로는 설계 단계에서부터 더 적극적으로 참여하고 테스트 코드 및 성능 최적화까지 고려하는 개발자로 성장하고자 합니다.

<br/>

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>
