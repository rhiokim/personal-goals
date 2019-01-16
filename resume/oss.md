# Open Source projects <small style="font-size: .5em; color: grey">(2012.03 ~ Present)</small>

### Flybook - 정적 문서 편집기

<!-- ![](https://github.com/rhiokim/flybook/blob/master/docs/basic/images/logo-250x250.png?raw=true "") -->
<img src="https://github.com/rhiokim/flybook/blob/master/docs/basic/images/logo-250x250.png?raw=true" width="100">

오픈소스 혹은 작은 라이브러리 하나를 만들더라도 그걸 사용하는 누군가에게 메뉴얼은 너무 중요하지만 그 과정과 문서화를 퍼블리싱하는 과정은 쉬운일은 아니기 때문에 소홀히 하는 경우가 많은데 이 과정을 손쉽게 만들기 위한 CLI 프로젝트

* 저장소 - https://github.com/rhiokim/flybook
* 공식사이트 - https://flybook.js.org/
* 소개 동영상 - https://www.youtube.com/playlist?list=PLfxSJBnYJIqgidc1uOxqe2FzhGPZEKxLI
* 사용기술 - React.js, Flowtype, Node.js, CircleCI

### FlyPoll - 투표 생성 서비스

OSS(Open Source Software) Governance 를 위한 서비스 중에 하나로 깃헙과 같은 협업 시스템에서 의사결정을 위해 필요한 투표 생성 서비스

* 저장소 - https://github.com/rhiokim/flypoll
* 데모
  * 투표생성기 - https://rhiokim.github.io/fly-poll-web/
  * 결과 - https://github.com/seouljs/seoul.js.org/blob/master/docs/meetups/2017.08.18(1st).md#schedule
* 사용기술 - Vue.js, Node.js, Google Firebase

### Gona - 할일 관리 도구 (CLI, Electron App)

<!-- ![](https://github.com/rhiokim/gona/blob/gh-pages/static/images/logo.png?raw=true "") -->

<img src="https://github.com/rhiokim/gona/blob/gh-pages/static/images/logo.png?raw=true" width="100">

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
* Wifi Finder: Node.js 구현한 와이파이 탐색기 CLI
  * https://github.com/rhiokim/wifi
* Seed Project: Node.js 과 최신 웹 기술을 기반으로 한 복잡한 Configuration 을 최소화하고 빠른 웹 애플리케이션 및 API 서버등을 개발하기 용이하도록 Pre-Configuration 한 프로젝트입니다.
  * https://github.com/rhiokim/.seed-cli
  * https://github.com/rhiokim/.seed
  * https://github.com/rhiokim/.seed-design-system-abstraction
  * https://github.com/rhiokim/.seed-api-server
  * https://github.com/rhiokim/react-boilerplate
  * https://github.com/rhiokim/.seed-next-app
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
* locally: 원하는 디렉토리를 웹 서버로 띄우기 위한 CLI 툴로 Python SimpleHTTPServer 모듈에 영감을 얻어 개발되었습니다.

### Work in progress

개인적인 관심분야의 지식을 쌓고 발전을 위해서 OSS 로 현재 진행중인 프로젝트에 대해 소개합니다.

* Dockerfile generator for SPA - https://github.com/rhiokim/gorae-spa-builder
> React.js, Vue.js 와 Next.js, Nuxt.js 와 같은 모던 웹 애플리케이션 개발 시에도 경우에 따라 NginX, Node.js Configuration 뿐만 아니라 Cloud 환경에 따라 최적의 Docker Configuration 을 요구한다. 이런 일련의 과정의 자동화 및 최적화를 제공하는 CLI 툴을 개발중입니다.
* Large Scale Frontend Architecture (writing) - https://github.com/rhiokim/large-scale-frontend
> 지난 수년간의 Javascript Application 개발 경험을 바탕으로 대규모의 팀과 애플리케이션을 구축하기 위한 방법론을 작성중입니다.
* Hyper Web Application Starter Kit - https://github.com/rhiokim/hybrid-vue-starter-kit
> 웹 기반 기술을 이용한 하이브리드 온 오프라인 동기화 웹 애플리케이션을 구축할 수 있도록 모던 웹 기술을 활용한 스타터 킷
* Design Ops & Design System
> 과거에 DevOps 의 영역이 고도화 되지 않던 시절에 우리는 NginX, Apache 서버 Configuration 을 수동으로 해왔습니다. 그리고 지난 몇년간 DevOps 라는 개념을 통해 서버 시스템의 자동화 고도화가 빠르게 발전하고 있습니다.
> 이와 동일한 맥락에 개발자들이 쉽게 접근하기 어려웠던 또 하나의 영역이 바로 사용자 엔드인데 이 부분의 자동화 즉 User Interface/Experience Design 을 체계적으로 자동화하려는 시도가 많아 이 부분의 공백을 채우기 위해 몇가지 필요한 지식을 수집하고 툴을 개발중입니다.
* Hyper Markdown & Markdown Worker
> Virtual DOM 에 영감을 얻어 Markdown 을 위한 가볍고 빠른 마크다운 엔진을 구현을 목표로 설계중이고 Markdown Worker 는 대용량 마크다운 문서의 Partial Parsing Engine 구현을 목표로 설계중입니다.