## Projects

### Triple - 실시간 여행가이드 앱

#### 투어 & 액티비티 커머스 서비스 / 8month

여행지에서 즐길 수 있는 다양한 투어, 티켓, 교통패스, 액티비티 등을 예약/구매 할 수 있는 커머스 서비스 및 내 예약관리 서비스

<!-- <video width="400" controls>
  <source src="./2018/media/triple_tour_and_ticket.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video> -->

* 역할
  * 투어티켓 e-commerce 프론트엔드 개발 전담
  * 트리플 <-> 공급사 이종 서비스간 주문폼 정보 매핑을 위한 예약폼 IDL 구현
  * 트리플 <-> 공급사 이종 서비스간 자동 주문 CLI 개발
  * 퍼포먼스 튜닝 및 E2E 테스트 케이스 관리
  * 모바일(iOS, Android) 웹뷰 연동에 발생하는 기술적인 이슈 대응
  * 내 예약 관리 웹 서비스 서스테이닝
* 성과
  * 안정적인 커머스 SPA 웹 애플리케이션 개발 구축
  * 주문폼 IDL 과 자동주문 CLI 를 통한 운영비용 일부 효율적으로 개선
* 사용기술
  * Vue.js, CSS/Stylus, Vuex, Vuetify, PWA, NginX, Docker, Puppeteer, Google Cloud CI/CD Pipeline, AWS, Cypress

#### 결재 시스템 내제화 프로젝트 / 8month

웹투어를 통한 호텔 결제 대행을 유지해오다 투어티켓 서비스의 확장으로 결제 내재화 프로젝트

* 역할
  * 모바일 결제 시스템 프론트엔드 개발 전담 (이니시스 및 네이버페이 연동)
  * 결제 테스트 환경 Sandbox 애플리케이션 개발
  * React.js 기반의 Next.js 에서 프레임웍 통일을 위해서 Vue.js 기반의 Nuxt.js 로 전환
* 성과
  * 숙박, 투어티켓 향후 추가될 비지니스 영역에서 필요한 안정적인 결제 시스템 내제화
  * 대행사를 통해 발생하던 유지운영 및 결제 비용 절감
  * 백엔드 개발자가 백오피스 프론트 애플리케이션 구현할 수 있도록 구축 및 기술 지원
* 사용기술
  * Next.js/Nuxt.js, CSS/Stylus, Express.js, Vue.js, Vuex, Vuetify

#### 호텔 예약 서비스 / 2month

여행에 필요한 호텔/숙박 정보 검색 및 예약 서비스

* 역할 - 서스테이닝
  * 호텔 상품정보 소셜 공유기능 구현
  * 디자인 2.0 통일화 개선작업에 필요한 Markup, CSS 개선
* 사용기술
  * Vue.js, Vuex, CSS/Stylus

#### OTA(Online Travel Agency) 플랫폼 / 6month

숙박(호텔) 정보를 제공하는 공급사(EAN, Agoda, GTA, 하나투어 등)와 숙박 정보가 필요한 판매 사이트를 연결해주기 위한 OTA(Online Travel Agency) 플랫폼 POC 개발

* 역할
  * 프론트엔드 개발 라이프 사이클(Develop/Build/Test/Deploy/Review) 에 대한 기술 리딩
  * 호텔 예약 사이트 POC 프론트엔드 개발
  * 호텔 공급 관리 및 호텔 숙박시설 관리 프론트엔드 개발 (aka HMS)
  * GRPC 서버 컴포넌트와 프론트엔드 연동을 위한 API Gateway 개발
* 사용기술
  * React.js, ES6, Redux, React-Router, Flowtype, Node.js, Jest, GRPC, Docker(Kubernetes), Jenkins, AWS

#### 회사 홈페이지 <small style="font-size: .8rem">https://triple-corp.com</small> / 3week

* 역할
  * Next.js 기반 SSR 웹 사이트 개발/운영 전담
* 사용기술
  * Next.js, React, Flowtype, Travis CI, AWS

### CDNetworks - Edge Computing R&D

#### New CDN(Content Distribution Network) platform - Edge Computing / 10month

Cache 와 Edge Computing 에 중점을 둔 오케스트레이션 플랫폼으로 CDNetworks 의 차세대 CDN 인프라 운영 방식을 개선하기 위한 프로젝트.

* 역할
  * 서비스(Job)와 애플리케이션(Task, App) 생성 관리 및 스케쥴 UI/UX 개발
  * DNS 호스팅 서비스 UI/UX 개발
  * Loopback.js 를 기반으로 한 API Gateway 구축 및 운영
  * Jenkins, Docker Registry, Nomad 기반 웹 애플리케이션 CI/CD 구축
* 성과
  * Regarcy Infrasructure 분석과 보완을 통해 새로운 CDN Platform 자동화 구축
* 사용기술
  * Backend: Nomad & Consul, Docker & Docker Swarm, Loopback.js (API Gateway), Node.js
  * Frontend: Angular2 (in Typescript), React.js
  * DevOps: Jenkins, Docker Registry

#### RASP WAF(Realtime Application Self-Protection Web Application Firewall) / 2month

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

#### 모바일 백엔드 플랫폼 baas.io / 5month

모바일 앱 개발을 위해 필요한 서버 환경에 구성요소(Resource, File Storage, User Authentication, Push & etc)를 자동화하여 설치 및 설정하고 플랫폼(iOS, Android, Javascript)별로 SDK 를 제공하여 모바일 앱 개발을 위한 백앤드 솔루션

* 역할
  * Baas.io 포털 프론트엔드 개발 파드리딩 및 스크럼 마스터
  * Notification Center, Analytics, User Profile UI 개발
  * 앱 개발자들을 위한 애플리케이션 관리 대쉬보드 프론트엔드 설계, Grunt.js 를 기반한 빌드, 배포 자동화 구축
  * Baas.io 기반 하이브리드 앱 개발을 위한 Javascript SDK 개발
* 성과
  * 안정적인 서비스 런칭 및 Baas.io 기반 애플리케이션 개발 고객 유치
* 사용기술
  * Frontend: Backbone.js, jQuery, require.js, grunt.js, twitter bootstrap, Node.js 등
  * Agile & Scrum 협업, Git WorkFlow 제안 및 실천법 공유

#### 스마트 콘텐츠 제작도구, 리얼목업 서비스 / 8month

모바일 앱 기획이 필요하거나 기획을 하는 사람이 이 서비스를 이용하여 실제와 동등한 수준의 모바일 앱을 손쉽게 프로토타이핑 해볼 수 있는 iPad 급 이상의 화면 너비 장치에서 제공되는 웹 서비스 <국책 사업>

* 역할
  * 기획 및 UI 개발
  * H3 컨퍼런스 2011 사이트 프론트엔드 개발 전담
* 사용기술
  * Frontend: Backbone.js, jQuery, require.js, Node.js

### NHN - Calendar, Ajax UI Lab

#### 캘린더 서비스 / 6month

친절한 나의 스케쥴 메니저로 캘린더 기반의 다양한 사용자 서비스

* 역할
  * 캘린더 서비스 서스테이닝 UI 개발 파트 리딩
  * 크로스 브라우징
* 성과
  * 사내 복잡도가 가장 높은 웹 애플리케이션으로 크로스 브라우저 이슈 대응 및 안정적인 서비스 운영
* 사용기술
  * Frontend: Jindo <네이버 사내 자바스크립트 라이브러리>, QUnit, Jenkins

#### 포토앨범 서비스 / 8month

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

### 판도라티비 - 개인 미디어 채널 판도라 글로벌 HD 동영상 서비스

개인 미디어 채널로 유튜브와 같은 세계적으로 인정받았던 동영상 서비스로 검색, 카테고리를 지원하는 동영상 포털 사이트, 개인화 인터넷 미디어 서비스

* 역할
  * 동영상 검색 카테고리 서비스 UI/UX 개발
  * 개인 미디어 방송국 Full Javascript 방명록 애플리케이션 개발 (2007년 Web2.0 이 주목받던 당시)
* 사용기술
  * Frontend: Javascript/Ajax, Prototype.js

### 나라아이넷 - 법률 검색 솔루션

* 역할
  * 킹스필드 (판례), 법누리 (대한민국 현행법령) 유지보수
  * [T&A Master](http://www.e-hoki.com/ta/index.html?ac=contents) - 일본 세무, 회계 법률 검색 솔루션 개발
* 사용기술
  * Delphi, Oracle, Sqlite

---

### 아이토비 - 창업

인터넷상에 존재하는 동영상들을 크롤링하여 정해진 시간 단위의 스냅샷과 스냅영상을 스파이럴(Spiral) 알고리즘을 통해 시각화하여 동영상 검색의 UX 를 개선하고자 했습니다.

* 역할
  * Adobe Flash 기반의 동영상 Visual Search Interface 연구 개발
  * 모바일 디바이스용 Flash lite 기반으로 포팅 (옴니아폰에 포팅)
  * Full Javascript 동영상 블로그 서비스 웹 개발
  * RTMP 기반 리얼타임 CCTV Interface 개발
  * 동영상 블로그 및 카테고리 서비스 프론트엔드 개발
* 사용기술
  * Flash (in Actionscript 3.x), PHP, Mysql, Javascript
* 데모 동영상 및 요약 정리자료
  * http://www.vimeo.com/9694100
  * http://www.vimeo.com/9691699
  * http://rhio.tistory.com/327
  * http://rhio.tistory.com/339

### 에크루 - 창업

군대 전역 후 무모하게 사업을 해보고 싶어 여성 의류 쇼핑몰을 600 만원으로 시작하여 사업자/통신파매업 신고부터 동대문 새벽시장 물건 사입, 쇼핑몰 개발/유지보수, 사진촬영까지 해보면서 약 10여개월을 유지하다. 월세 35만원을 낼돈이 없어서 사업 종료, 인생에 있어서 좋은 경험.

* 역할
  * Photoshop 으로 쇼핑몰 디자인
  * PHP + Mysql 쇼핑몰 구현
  * Apache + PHP + Mysql 서버 설정 및 운영 관리
* 사용기술
  * PHP, Mysql, HTML/CSS, Photoshop

### 이노솔루스 - 창업

대학 생활때 졸업한 선배와 함께 창업 (목포시 소프트웨어 경진대회 일반부 장려상 수상)

* 역할
  * 법률 검색, 법률 사무소 업무 지원 포털 사이트 개발
  * 법률 ERP 솔루션 개발 및 웹 서비스(PHP) 간 통신 모듈 개발
* 사용기술
  * Delphi, Interbase, PHP