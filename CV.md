# Curriculum Vitae

## About Me

| Now  | Future      |
|:---------:|:--------------:|
|![](https://avatars3.githubusercontent.com/u/145777?v=3&u=d2a7dc8cc7be849d1e3cfbb98d1550708ccd1c2b&s=175)<br/> 김양원(Rhio Kim) | ![](./media/douglas_crock_ford.jpeg) ![](./media/babros.jpg)<br>Douglas Crockford + Bob Ross

| 연락처 | 이메일 | 생년월일 | 주소 |
|--------|-------|-------|-----|
| 010-8347-9747 | rhio.kim@gmail.com | 1980-04-05 | 서울시 강남구 논현로 106길 |

현재와 미래의 밥로스와 더글라스 크록포드와 같은 사람이 되기를 꿈꿉니다.

안녕하세요! 개발자 김양원입니다.
이제 경력과 기술은 년차로 전문성을 인정받는 것보다 개발자로서 세상과 사회를 계속 발전시키는 구성원이 되려고 늘 노력합니다.

더불어 조직에서 목표를 달성하고 문제를 해결하기 위해 필요한 기술적인 요구를 꾸준히 습득함을 게을리하지 않습니다.

성숙한 개발자 문화를 꿈꾸고 실천합니다. 넘기 어려워보이는 비지니스 목표나 복잡하고 어려울것 같은 기술적인 이슈도  구성원 각자의 성장과 동시에 더욱더 투명한 비젼을 계획할 수 있다고 생각합니다.

* Github: https://github.com/rhiokim
* Twitter: https://twitter.com/rhiokim
* Facebook: https://facebook.com/rhiokim

<br/><br/><br/><br/><br/>

## History

| 기  간             | 회사 이름     | 부 문                         |
|------------------|:----------:|------------------------------|
| 2017.06.28 - 현재 | (주)트리플 | 투어티켓 e-커머스, OTA(Online Travel Agency) 플랫폼 개발 |
| 2015.08.16 - 2017.06.27 | (주)씨디네트웍스 | CDN 인프라 오케스트레이션 서비스/Portal 3.0 개발 |
| 2013.04.09 - 2015.07    |   OSS   | 오픈 소스 프로젝트 (하루패드)       |
| 2011.10.17 - 2013.04.09 | KTH(주)        | 플랫폼 개발팀, Baas 개발팀  |
| 2010.05.17 - 2011.09.15 | NHN(주)        | 캘린더 개발팀, Ajax UI 랩  |
| 2008.08.01 - 2010.03.02 | (주)아이토비     | 동영상 검색 시각화 선임연구원 |
| 2007.02.21 - 2008.08.14 | (주)판도라티비    | 웹 개발팀                |
| 2006.05.01 - 2007.02.07 | 에크루          | 여성 의류(쇼핑몰) 창업, 운영, 개발 |
| 2003.03.16 - 2004.03.16 | (주)나라아이넷    | 법령, 판례 검색 솔루션 개발   |
| 2001.04.01 - 2002.11.18 | (주)이노솔루스    | 법률 상담 솔루션 개발       |

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

## Projects

### Triple - 실시간 여행가이드 앱

#### 투어 & 액티비티 커머스 서비스

여행지에서 즐길 수 있는 다양한 투어, 티켓, 교통패스, 액티비티 등을 예약/구매 할 수 있는 커머스 서비스 및 내 예약관리 서비스

<!-- <video width="400" controls>
  <source src="./2018/media/triple_tour_and_ticket.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video> -->

* 역할
  * 투어티켓 커머스 상품 전시, 상세, 예약, 주문에 필요한 프론트엔드 개발 전담
  * 내 예약 관리 서비스 서스테이닝
  * 트리플 -> 공급사(waug.com) 이종 서비스간 주문폼 정보 매핑을 위한 예약폼 IDL 구현
  * Google Lighthouse 를 이용한 웹 애플리케이션 퍼포먼스 튜닝
  * Cypress.io 를 이용한 E2E 테스트 케이스 관리
  * iOS, Android 연동에 발생하는 기술적인 이슈 대응
  * Vue.js SPA + NginX + AWS + Google Cloud CI/CD Pipeline 운영

* 사용기술
  * Vue.js, Vuex, Vue-Router, Vuetify, PWA, NginX, Docker, Google Cloud Build, AWS, Cypress

#### 결재 시스템 내제화 프로젝트

웹투어를 통한 호텔 결제 대행을 유지해오다 투어티켓 서비스의 확장으로 결제 내재화 프로젝트

* 역할
  * 모바일 결제 시스템 프론트엔드 개발 전담 (이니시스 및 네이버페이 연동)
  * 결제 테스트 환경 Sandbox 애플리케이션 개발
  * React.js 기반의 Next.js 에서 프레임웍 통일을 위해서 Vue.js 기반의 Nuxt.js 로 전환
* 사용기술
  * Next.js/Nuxt.js, Express, Vue.js, Vuex, Vue-Router, Vuetify

#### 호텔 예약 서비스

여행에 필요한 숙박 정보 검색 및 예약 서비스

* 역할 - 서스테이닝
  * 호텔 상품정보 소셜 공유기능 구현
  * 디자인 2.0 통일화 개선작업에 필요한 Markup, CSS 개선
* 사용기술
  * Vue.js

#### OTA(Online Travel Agency) 플랫폼

숙박(호텔) 정보를 제공하는 공급사(EAN, Agoda, GTA, 하나투어 등)와 숙박 정보가 필요한 판매 사이트를 연결해주기 위한 OTA(Online Travel Agency) 플랫폼, 6개월간 POC 개발

* 역할
  * 프론트엔드 개발 라이프 사이클(Develop/Build/Test/Deploy/Review) 에 대한 기술 리딩
  * 호텔 예약 사이트 POC 프론트엔드 개발
  * 호텔 공급 관리 및 호텔 숙박시설 관리 프론트엔드 개발
  * GRPC 서버 컴포넌트와 프론트엔드 연동을 위한 API Gateway 개발
* 사용기술
  * React.js, ES6, Redux, React-Router, Flowtype, Node.js, Jest, GRPC, Docker(Kubernetes), Jenkins, AWS

#### 회사 홈페이지 <small style="font-size: .8rem">https://triple-corp.com</small>

* 역할
  * Next.js 기반 SSR 웹 사이트 개발
  * Travis CI + AWS CI/CD Pipeline 운영 관리
* 사용기술
  * Next.js, React, Flowtype, Travis CI, AWS

### CDNetworks - Edge Computing R&D

#### New CDN(Content Distribution Network) platform - Edge Computing

Cache 와 Edge Computing 에 중점을 둔 오케스트레이션 서비스로 CDNetworks 의 차세대 CDN 인프라 운영 방식을 개선하기 위한 프로젝트.

* 역할
  * 서비스(Job)와 애플리케이션(Task, App) 생성 관리 및 스케쥴 UI/UX 개발
  * DNS 호스팅 서비스 UI/UX 개발
  * Loopback.js 를 기반으로 한 API Gateway 구축 및 Backend 컴포넌트 컴포지션
  * 기타 서비스 UI/UX 디자인 및 마크업
  * Jenkins, Docker Registry, Nomad 기반 웹 애플리케이션 CI/CD 구축
  * Docker 기반으로 모든 웹 애플리케이션(API Gateway, SPA) 및 컴포넌트 컨테이너라이징
* 사용기술
  * Backend: Nomad & Consul, Docker & Docker Swarm, Loopback.js (API Gateway), Node.js
  * Frontend: Angular2 (in Typescript), React.js
  * DevOps: Jenkins, Docker Registry

#### RASP WAF(Realtime Application Self-Protection Web Application Firewall)

이 프로젝는 런타임의 웹 애플리케이션의 DDoS 나 SQL Injection, XSS 등과 같은 공격이나 취약점 접근을 탐지하여 Layer 3/4 와 7 보호를 할 수 있는 Virtual Appliance 형태의 WAF 솔루션.

* 역할
  * 실시간 NginX 로그 수집을 위한 ZeroMQ/Node.js 기반 Pub/Sub 클러스터링 구축
  * Kernel Level Firewall 컨트롤을 위한 IPtables Wrapping API 서버 개발
  * WAF 운영 관리를 위한 Admin Dashboard UI 및 API 서버 개발
  * NAXSI(Nginx Anti XSS & SQL Injection) Rule/Whitelist 관리 UI 및 API 서버 개발
* 사용기술
  * Backend: Docker, Nginx + NAXSI, ZeroMQ, Elastic Search, IPtables (in Netfilter), ZeroMQ Pub/Sub clustering based on Node.js, LevelDB
  * Frontend: React.js + ES6 + Node.js

### KTH - 모바일 백엔드 플랫폼 <small style="font-size: .8rem">https://baas.io</small>

#### 모바일 백엔드 플랫폼 baas.io

모바일 앱 개발을 위해 필요한 서버 환경에 구성요소(Resource, File Storage, User Authentication, Push & etc)를 자동화하여 설치 및 설정하고 플랫폼(iOS, Android, Javascript)별로 SDK 를 제공하여 모바일 앱 개발을 위한 백앤드 솔루션

* 역할
  * Baas.io 포털 프론트엔드 개발 파드리딩 및 스크럼 마스터
  * Notification Center, Analytics, User Profile UI 개발
  * 앱 개발자들을 위한 애플리케이션 관리 대쉬보드 프론트엔드 아키텍쳐 설계, Grunt.js 를 기반한 개발, 빌드, 배포 자동화 구축
  * 하이브리드 앱 개발을 위한 Javascript SDK 개발
* 사용기술
  * Frontend: Backbone.js, jQuery, require.js, grunt.js, twitter bootstrap, Node.js 등
  * Agile & Scrum 협업, Git WorkFlow 제안 및 실천법 공유

#### 스마트 콘텐츠 제작도구, 리얼목업 서비스

모바일 앱 기획이 필요하거나 기획을 하는 사람이 이 서비스를 이용하여 실제와 동등한 수준의 모바일 앱을 손쉽게 프로토타이핑 해볼 수 있는 iPad 급 이상의 화면 너비 장치에서 제공되는 웹 서비스 <국책 사업>

* 역할
  * 기획 및 UI 개발
* 사용기술
  * Frontend: Backbone.js, jQuery, require.js, Node.js

#### H3 컨퍼런스 2011 사이트 구축

KTH 에서 매년 진행하는 H3 개발자 컨퍼런스 사이트

* 역할
  * 전체 사이트 UI 개발 전담
* 사용기술
  * Frontend: jQuery, Node.js

### NHN - Calendar, Ajax UI Lab

#### 캘린더 서비스

친절한 나의 스케쥴 메니저로 캘린더 기반의 다양한 사용자 서비스

* 역할
  * 캘린더 서비스 서스테이닝 UI 개발 파트 리딩
  * 크로스 브라우징
* 사용기술
  * Frontend: Jindo <네이버 사내 자바스크립트 라이브러리>, QUnit, Jenkins

#### 포토앨범 서비스

flickr 와 같이 개인 사진을 관리하는 서비스 <현재는 Ndrive 와 통합됨>

* 역할
  * 이미지 뷰어 및 사진관리 Full Javascript Application 개발
* 사용기술
  * Jindo <네이버 사내 자바스크립트 라이브러리>, QUnit

#### 사내 자바스크립트 전문 강사 활동

1. 숨겨진 자바스크립트 정복 가이드 : http://scr.bi/pOTPNI
2. 자바스크립트 기초 : http://scr.bi/nioQBv
3. 자바스크립트 고급 : http://scr.bi/np4L77
4. Ajax UI 개발 실무 기본 : http://scr.bi/pUQtFh

### 아이토비 - Visual Search Interface R&D

#### 동영상 블로그 및 카테고리 서비스

인터넷상에 존재하는 동영상들을 크롤링하여 정해진 시간 단위의 스냅샷과 스냅영상을 스파이럴(Spiral) 알고리즘을 통해 시각화하여 동영상 검색의 UX 를 개선하고자 했습니다.

* 역할
  * Adobe Flash 기반의 동영상 Visual Search Interface 연구 개발
  * 모바일 디바이스용 Flash lite 기반으로 포팅 (옴니아폰에 포팅)
  * Full Javascript 동영상 블로그 서비스 웹 개발
  * RTMP 기반 리얼타임 CCTV Interface 개발
* 사용기술
  * Flash (in Actionscript 3.x), PHP, Mysql, Javascript
* 데모 동영상 및 요약 정리자료
  * http://www.vimeo.com/9694100
  * http://www.vimeo.com/9691699
  * http://rhio.tistory.com/327
  * http://rhio.tistory.com/339

### 판도라티비 - 개인 미디어 채널 판도라 글로벌 HD 동영상 서비스

개인 미디어 채널로 유튜브와 같은 세계적으로 인정받았던 동영상 서비스로 검색, 카테고리를 지원하는 동영상 포털 사이트, 개인화 인터넷 미디어 서비스

* 역할
  * 동영상 검색 카테고리 서비스 UI/UX 개발
  * 개인 미디어 방송국 Full Javascript 방명록 애플리케이션 개발 (2007년 Web2.0 이 주목받던 당시)
* 사용기술
  * Frontend: Javascript, Prototype.js

### 에크루 - 여성 의류 쇼핑몰 창업

군대 전역 후 무모하게 사업을 해보고 싶어 여성 의류 쇼핑몰을 600 만원으로 시작하여 사업자/통신파매업 신고부터 동대문 새벽시장 물건 사입, 쇼핑몰 개발/유지보수, 사진촬영까지 해보면서 약 10여개월을 유지하다. 월세 35만원을 낼돈이 없어서 사업 종료, 인생에 있어서 좋은 경험.

* 역할
  * Photoshop 으로 쇼핑몰 디자인
  * PHP + Mysql 쇼핑몰 구현
  * Apache + PHP + Mysql 서버 설정 및 운영 관리
* 사용기술
  * PHP, Mysql, HTML/CSS, Photoshop

### 나라아이넷 - 법률 검색 솔루션

#### 킹스필드 (판례), 법누리 (대한민국 현행법령)
대한민국 법령, 판례 등 법률 관련 자료 검색을 위한 프로그램

* 역할
  * Delphi 기반 데스크탑 판례, 법률검색 애플리케이션 개발 및 검색엔진 유지보수
* 사용기술
  * Delphi, Oracle, Sqlite

#### T&A Master - 일본 세무, 회계 법률 검색 솔루션

일본 세무, 회계 관련 법률 검색 솔루션 http://www.e-hoki.com/ta/index.html?ac=contents

* 역할
  * 일본 세무, 회계관련 법률 검색 데스크탑 애플리케이션 개발
  * Namzu Search Engine 을 이용한 일본 법령 데이터 인덱싱 자동화
* 사용기술
  * Delphi

### 이노솔루스 - 창업

대학 생활때 졸업한 선배와 함께 창업 (목포시 소프트웨어 경진대회 일반부 장려상 수상)

* 역할
  * 법률 검색, 법률 사무소 업무 지원 포털 사이트 개발
  * 법률 ERP 솔루션 개발 및 웹 서비스(PHP) 간 통신 모듈 개발
* 사용기술
  * Delphi, Interbase, PHP

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

## Open Source projects <small style="font-size: .5em; color: grey">(2012.03 ~ Present)</small>

### Work in progress

개인적인 관심분야의 지식을 쌓고 발전을 위해서 OSS 로 현재 진행중인 프로젝트에 대해 소개합니다.

* Dockerfile generator for SPA - https://github.com/rhiokim/gorae-spa-builder
> React.js, Vue.js 와 Next.js, Nuxt.js 와 같은 모던 웹 애플리케이션 개발 시에도 경우에 따라 NginX, Node.js Configuration 뿐만 아니라 Cloud 환경에 따라 최적의 Docker Configuration 을 요구한다. 이런 일련의 과정의 자동화 및 최적화를 제공하는 CLI 툴을 개발중입니다.
* Large Scale Frontend Architecture (writing) - https://github.com/rhiokim/large-scale-frontend
> 지난 수년간의 Javascript Application 개발 경험을 바탕으로 대규모의 팀과 애플리케이션을 구축하기 위한 방법론을 작성중입니다.
* Design Ops & Design System
> 과거에 DevOps 의 영역이 고도화 되지 않던 시절에 우리는 NginX, Apache 서버 Configuration 을 수동으로 해왔습니다. 그리고 지난 몇년간 DevOps 라는 개념을 통해 서버 시스템의 자동화 고도화가 빠르게 발전하고 있습니다.
> 이와 동일한 맥락에 개발자들이 쉽게 접근하기 어려웠던 또 하나의 영역이 바로 사용자 엔드인데 이 부분의 자동화 즉 User Interface/Experience Design 을 체계적으로 자동화하려는 시도가 많아 이 부분의 공백을 채우기 위해 몇가지 필요한 지식을 수집하고 툴을 개발중입니다.
* Hyper Markdown & Markdown Worker
> Virtual DOM 에 영감을 얻어 Markdown 을 위한 가볍고 빠른 마크다운 엔진을 구현을 목표로 설계중이고 Markdown Worker 는 대용량 마크다운 문서의 Partial Parsing Engine 구현을 목표로 설계중입니다.

### Flybook - 정적 문서 편집기

![](https://flybook.js.org/basic/images/logo-250x250.png "" "width: 100px")

오픈소스 혹은 작은 라이브러리 하나를 만들더라도 그걸 사용하는 누군가에게 메뉴얼은 너무 중요하지만 그 과정과 문서화를 퍼블리싱하는 과정은 쉬운일은 아니기 때문에 소홀히 하는 경우가 많은데 이 과정을 손쉽게 만들기 위한 CLI 프로젝트

* 저장소 - https://github.com/rhiokim/flybook
* 공식사이트 - https://flybook.js.org/
* 소개 동영상 - https://www.youtube.com/playlist?list=PLfxSJBnYJIqgidc1uOxqe2FzhGPZEKxLI
* 사용기술 - React.js, Flowtype, Node.js, CircleCI

### FlyPoll - 투표 생성 서비스

OSS(Open Source Software) Governance 를 위한 서비스 중에 하나로 깃헙과 같은 협업 시스템에서 의사결정을 위해 필요한 투표 생성 서비스

* 저장소 - https://github.com/rhiokim/flypoll
* 데모 - https://rhiokim.github.io/fly-poll-web/
* 사용기술 - Vue.js, Node.js, Google Firebase

### Gona - 할일 관리 도구 (CLI, Electron App)

![](https://raw.githubusercontent.com/rhiokim/gona/gh-pages/static/images/logo.png "" "width:100px")

일렉트론(Electron) 기반 프로젝트로 CLI 도 함께 지원하는 할일 관리 데스크탑 애플리케이션

* 저장소 - https://github.com/rhiokim/gona/
* 공식사이트 - https://rhiokim.github.io/gona/
* 사용기술 - Electron, Node.js, Flowtype, CircleCI

### RASP(Runtime Application Self-Protection) WAF Virtual Appliance

이 프로젝는 런타임의 DDoS 나 SQL Injection, XSS 등과 같은 웹 취약점 접근을 실시간으로 탐지하여 Layer 3/4 와 7 보호를 할 수 있는 Virtual Appliance 형태의 WAF 솔루션입니다.

![](https://raw.githubusercontent.com/rhiokim/thorn/master/assets/RASP_WAF.001.png "" )

구조에 대해 간단히 설명하면 웹 애플리케이션(NginX)으로 들어오는 모든 웹 취약점을 NAXSI(엑세스 패턴 분석 모듈, mod_security 와 유사함) 로 분석해 낸 후 이 결과를 실시간으로 서비스에 반영함으로써 취약 접근에 대해서 Netfilter, IPtable 을 이용해 커널 레벨의 방화벽과 웹 애플리케이션(NginX) 레벨의 접근을 실시간으로 보호하게 됩니다.

일반적으로 웹 엑세스 로그는 무수히 많다보니 웹 애플리케이션과 분리된 분석 시스템을 구축하는데 이를 위해 ZeroMQ 와 같은 Message Queuing System 을 분산으로 구축하여 로그를 수집하여 저장하고 중복되는 안티 패턴 접근을 검색하고 시각화 데이터를 만들기 위해 Elastic Search 를 이용하였습니다.

![](https://raw.githubusercontent.com/rhiokim/thorn/master/assets/RASP_WAF.002.png "")

다음은 이 프로젝트를 구성하기 위해 사용된 오픈소스 및 구현체에 대해 기술합니다.

* WAF Core engine (NginX + NAXSI + ZeroMQ Client)
  * https://github.com/rhiokim/thorn
* Elastic Search 5.x
* Log Aggregator and Pre-Processor (ZeroMQ + Node.js)
  * https://github.com/rhiokim/thorn-zmq-sub
* IPTables control daemon (Node.js + IPtables)
  * https://github.com/rhiokim/thorn-netfilter
* Dashboard (React.js + ES6 + Blueprint UI Toolkit)
  * UI: https://github.com/rhiokim/thorn-ui
  * API Server: https://github.com/rhiokim/thron-api

### Gorae

![](https://raw.githubusercontent.com/rhiokim/gorae/master/media/Gorae.001.png)

**Gorae**는 Docker, Docker Swarm, Docker Image Registry 그리고 Continuous Deployment(CD)를 담당하는 파이프 라인을 GUI로 관리하기 위한 도구의 집합입니다.

* Gorae for Docker
> Docker 호스트상에 이미지, 컨테이너, 네트워크, 볼륨을 UI 로 관리하기 위한 도구
* Gorae Swarm for Docker Swarm
> Docker 기반에 복잡한 인프라스트럭쳐 운영과 서비스 오케스트레이션에서 요구되는 서비스 프로비져닝, 스케쥴링 및 스케일 인/아웃, 상태 모니터링 등을 UI 로 관리하기 위한 도구
* Gorae Registry from Docker distribution
> Docker Image Resgiry 용 GUI 도구
* Gorae Pipe for CI/CD pipline tool with Docker Swarm and Registry
> DVCS(github, bitbucket, gitlab), CI(jenkins, travis, cicleci) 와 연동되어 Gorae Swarm 유연하게 동작하는 CI/CD 용 파이프라인 관리 도구

![](https://raw.githubusercontent.com/rhiokim/gorae/master/media/Gorae.002.png)

다음은 이 프로젝트를 구성하기 위해 사용된 오픈소스 및 구현체에 대해 기술합니다.

* Gorae, Gorae Swarm
  * https://github.com/rhiokim/gorae
* Gorae Image Registry
  * https://github.com/rhiokim/gorae-registry
* Gorae Pipe
  * https://github.com/rhiokim/gorae-github-pipe

위 3가지 프로젝트는 React.js, ES6, Material Design 기반으로 개발되었고 아래 API Server 를 통해 호스트에 설치된 Docker 와 UDP 통신하게 됩니다.

* Gorae API Server (Express.js + Unix Domain Socket Wrapper)
  * https://github.com/rhiokim/gorae-server

**발표자료**
* Node.js 2016 Conference "**Docker, Docker Swarm mangement tool - Gorae**" https://www.slideshare.net/Rhiokim/docker-docker-swarm-mangement-tool-gorae

### 하루패드 (Haroopad)

![](https://raw.githubusercontent.com/rhiokim/haroopad/gh-pages/assets/images/logo-128x128x32.png "")

크로스 플랫폼 마크다운 에디터로 마크다운 문서 작성 시 요구되는 최신의 기능들을 제공하며 웹 기술을 이용한 응용 프로그램으로 여러 곳에서 소개되고 사용되고 있습니다.

다음은 이 프로젝트를 구성하기 위해 사용된 오픈소스 및 구현체에 대해 기술합니다.

NW.js(node-webkit), Node.js, Marked.js, codemirror, twitter bootstrap, backbone.js, grunt.js, less 등의 약 20여 가지의 오픈 소스를 조합하여 개발되어졌습니다.

* https://github.com/rhiokim/haroopad

더불어 이 프로젝트를 통해 부가적인 기술적 및 운영 경험을 얻게 되었습니다.

* Window(MSI Installer, Linux(Deb, tar.gz), Mac OSX(dmg)용 패키지 자동화 도구
* 애플리케이션 사용 통계 및 분석
* 언어팩 자동 업데이트 기능
* 사용자 피드박 수집 및 인터렉션 경험

**국내 외 보도자료**

* inforworld.com Beyond the Web: 10 surprising Node.js projects
  * http://bit.ly/1tpeM0u
* Moongift.jp : Haroopad - 開発者にぴったりなMarkdownエディタ
  * http://bit.ly/1iDipKh
* Jupiter Broadcasting “Linux Action Show” 322 - “Haroopad change my life”
  * http://bit.ly/1thoJ1N
* Linux User 독일 매거진 2014. 09월호 P.72~73 - 실시간 미리보기가 내장된 마크다운 편집기 Haroopad
  * http://www.linux-community.de/Internal/Artikel/Print-Artikel/LinuxUser/2014/09/Ausgezeichnet
* NIPA(정보통신 산업진흥원) 글로벌 공개 소프트웨어 지원 사업
  * http://www.oss.kr/103714
* 2013년 유망 공개 소프트웨어 선정
  * http://www.oss.kr/oss_notice/oss_repository12/103649

### 하루프레스 (haroopress)

하루프레스는 **하루**라는 순 우리말과 **프레스**(press)라는 단어의 조합으로 하루에 이야기를 작성하여 발행하는 매우 간단한 블로그 엔진이라는 의미에서 하루프레스 라고 이름을 지었습니다.

그리고 기술적으로는 웹 서버와 데이터베이스가 필요 없는 정적 페이지 기반의 블로깅 엔진입니다. 정적 페이지 기반 블로그란 PHP 로 만들어진 워드 프레스와 같이 서버측에서 프로그램이 동작하는 것이 아닌 블로그를 구성하는 모든 페이지를 HTML 로 생성하는 프로그램을 말합니다.

하루프레스는 블로그를 위한 모든 콘텐츠를 정적 페이지(HTML)로 생성합니다. 그리고 이렇게 생성된 페이지들을 인터넷이 되지 않는 개인 컴퓨터에서 볼 수도 있고 Github 의 정적 페이지 서비스를 이용해 퍼블리싱도 할 수 있습니다.

그리고 HTML5, CSS3 을 이용한 테마와 플러그인도 존재하여 다양한 편리한 기능을 부가적으로 제공합니다.

그리고 마지막으로 하루프레스의 가장 중요한 목표는 블로그가 필요한 사람들보다 블로깅을 하려는 사람들에게 불필요한 서버 구성, 데이터 베이스 설치 등을 잊고 글 쓰는 곳에만 몰입할 수 있도록 하는 데에 있습니다.

다음은 이 프로젝트를 구성하기 위해 사용된 오픈소스 및 구현체에 대해 기술합니다.

* Haroopress (Express.js + Node.js)
  * https://github.com/rhiokim/haroopress

### 마크다운 스타일 시트 표준화 (markdown css)

마크다운 포맷은 HTML 로 변환될때 구조화된 마크업으로 컴파일되는데 이때 좀더 성숙한 페이지를 구성하기 위한 스타일을 less 를 이용해 손쉽게 설정할 수 있도록 해줍니다.

이 표준화 프로젝트는 [하루패드](http://pad.haroopress.com)에 사용자 스킨을 위해 시작된 서브 프로젝트입니다.

### 기타 오픈 소스 프로젝트

* Rhino Icon: 키노트로 그린 코뿔소(자바스크립트를 대표하는 동물) 아이콘
	* https://github.com/rhiokim/rhino-icons
	![](https://raw.githubusercontent.com/rhiokim/rhino-icon/master/media/intro.png)
* babel-plugin-gist: gist 에 등록된 Javascript code snippet 을 바로 dynamic import 해서 사용할 수 있는 플러그인
  * https://github.com/rhiokim/babel-plugin-gist
* Docker Icon: 키노트로 그린 도커 아이콘
	* https://github.com/rhiokim/docker-icons
	![](https://raw.githubusercontent.com/rhiokim/docker-icons/master/media/intro.png)
* Wifi Finder: Node.js 구현한 와이파이 탐색기
  * https://github.com/rhiokim/wifi
* Seed Project: Node.js 과 최신 웹 기술을 기반으로 한 복잡한 Configuration 을 최소화하고 빠른 웹 애플리케이션 및 API 서버등을 개발하기 용이하도록 Pre-Configuration 한 프로젝트입니다.
  * https://github.com/rhiokim/.seed-cli
  * https://github.com/rhiokim/.seed
  * https://github.com/rhiokim/.seed-design-system-abstraction
  * https://github.com/rhiokim/.seed-api-server
  * https://github.com/rhiokim/react-boilerplate
  * https://github.com/rhiokim/.seed-next-app
* locally: 원하는 디렉토리를 웹 서버로 띄우기 위한 CLI 툴로 Python SimpleHTTPServer 모듈에 영감을 얻어 개발되었습니다.
  * [https://github.com/rhiokim/locally](https://github.com/rhiokim/locally)
* grunt-sloc : Grunt.js 플러그인으로 물리적 코드 라인에 대한 다양한 정보를 보여준다.
	* https://github.com/rhiokim/grunt-sloc
* IOT: 웹(HTML5) 기반 홈 오토메이션 시스템 개발 연구
  * 하이브리드 홈 오토메이션 시스템 : https://vimeo.com/51812784
  * 웹 기반 음성인식 전원제어 : https ://vimeo.com/33859298
  * 조도 센서, 온도 센서, 무접점 릴레이 : https://vimeo.com/51812784
  * IR 송/수신센서를 이용한 웹 리모콘 : https://vimeo.com/53157569
  * webkit-speech API 를 이용한 LED 제어 : https://vimeo.com/33859298
* 맥 키노트용 테마 : http://rhiokim.github.io/keynote-themes/
* Mou 에디터 to 에버노트 : http://rhiokim.github.io/Mou2Evernote/

<!--
### 진행했던 프로젝트 <small>(2013.05 ~ 2013.05)</small>

* 사운드 앤 샷
  - 소개
  > 모바일 앱으로 현재 3명의 멤버가 개발 진행 중
  - 사용기술
  > Node.js, Mongodb, APNS(Apple Notification), Gumby2 (Responsive CSS Framework)
  - 역할
  > RESTful API 디자인, 시스템(Node.js, Mongodb, APNS) 엔지니어링, 웹 사이트 개발

* 하루티비
  - 소개
  > 웹 기반 기술로 구글 Chromimum 과 Paspberry Pi를 기반으로 하는 셋탑박스
  - 사용기술
  > Chromimum, ARM용 리눅스(Archi, Debian, Raspbian), Node.js, Raspberry Pi & Arduino
-->

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

## Activities

### Plan & Retrospects

회고는 2012년 부터 꾸준히 해오고 있는데 관리 소홀로 아래의 4년도의 회고만 남아있습니다. 2016년 부터는 계획을 작성하고 그 계획을 바탕으로 실질적인 실행과 액션에 대한 결과와 함께 회고를 진행하고 있습니다.

* 2018 plan / 2018 retrospect
* 2017 plan / 2017 retrospect
* 2016 plan
* [2012 retrospect](http://rhio.tistory.com/)

### Communities

Seoul.js   | Topic                           | Presentation
:---------:|---------------------------------|---------------------------
2018.08.18 | [Seoul.js first meetup](http://bit.ly/2EVtnAw)           | http://bit.ly/2QX4Nps, 오거나이징
2018.07.27 | [Lighting talk 2018](http://bit.ly/2ETaQ7O) | 오거나이징

FRENDS     | Topic                           | Presentation
:---------:|---------------------------------|---------------------------
2010.05    | Appcelerator Titainum           | http://slidesha.re/9HIVdw
2010.10    | Writing Native Addon in Node.js | http://scr.bi/9eq8ea
2011.05    | Function Work in JavaScript     | http://slidesha.re/qu9NZp
2011.07    | JavaScript History              | http://slidesha.re/qyGOCa
2012.06    | Static Blog engine Haroopress   | http://slidesha.re/PO3JL7

### 교육, 세미나

행사 / 모임      |   주제                             |  규모       | 비고
---------------|----------------------------------|------------|------------
LG R&D Campus  | 실습을 통한 Node.js 프로그래밍 이해하기  | 30         |
               | Node.js 의 본질, 서버 아키텍쳐의 영향력  |            |
               | 에코 시스템에 대한 이해와 활용           |            |

### 컨퍼런스, 강연

행사 / 모임        |   주제                                    |  규모   | 관련자료
----------------|------------------------------------------|:------:|--------------
FEConf Korea 2017 | Javascript fatigue | 200    | [http://bit.ly/2qGjWOZ](http://bit.ly/2qGjWOZ)
Seoul.js Meetup (2017) | 문서화에 날개를 달아주는 Flybook CLI | 200    | [http://bit.ly/2qFlE39](http://bit.ly/2qFlE39)
OSS 개발자 포럼 오픈소스 개발자 이야기 (2017) | 나는 오픈소스로 화가가 되었다 | 200    | [http://bit.ly/2D7IEKY](http://bit.ly/2D7IEKY)
OSS 개발자 포럼 Git/Github 세미나 (2017) | 나는 오픈소스로 요리를 배웠다   | 40    | [http://bit.ly/2ofWsKP](http://bit.ly/2ofWsKP)
Node.js 컨퍼런스 (2016) | Docker, Docker Swarm mangement tool - Gorae   | 100    | [http://bit.ly/2mWX5JE](http://bit.ly/2mWX5JE)
Node.js 컨퍼런스 (2012) | Node.js 기반 정적 페이지 블로그 엔진, 하루프레스   | 250    | [http://bit.ly/UjWNta](http://bit.ly/UjWNta)
KTH H3 컨퍼런스    | 2012년 우리가 모르는 Node.js 로 할 수 있는 몇가지 | 1,000  | [http://bit.ly/SP17Bn](http://bit.ly/SP17Bn)
                | 2011년 웹 소프트웨어 시장의 새로운 롤 자바스크립트   | 700     | [http://slidesha.re/SDs5HZ](http://slidesha.re/SDs5HZ)
웹앱퓨처콘 2011    | 자바스크립트 전성시대                          | 300     | [http://bit.ly/fVNx5I](http://bit.ly/fVNx5I), [http://bit.ly/p0ZCoT](http://bit.ly/p0ZCoT)
웹 데브 모바일      | JavaScript Developer Generation          | 120     |
                | Hybrid WebApp Platform Appcelerator Titanium | 50  | [http://scr.bi/nrY7tb](http://scr.bi/nrY7tb)

## 기타 소셜 액티비티 스트림

Site       | URL
:---------:|-------------------------------------
Slideshare | http://www.slideshare.net/rhio.kim
Blog       | http://rhio.tistory.com

## Licenses

License Name | License No. | Organzation | Date
-------------|-------------|-------------|---------
정보처리기사    | 02202200156M | 한국 산업인력 공단 | 2002.8.19
정보처리 산업기사 | 02201200446M | 한국 산업인력 공단 | 2002.06.03
네트워크 관리사 |  | 한국 정보통신자격협회 |

## ETC

* 초정밀 성격진단 mgram 결과 - https://mgram.me/ko/share/LNjqQmn-no985SyvCpP?

---
위의 내용은 사실임을 증명하며, 만약 사실이 아닐 경우 MIT 라이센스로 이 정보를 개인적인 용도로 이용할 수 있도록 허용합니다.

![](https://raw.githubusercontent.com/rhiokim/gorae/master/media/sign.png)