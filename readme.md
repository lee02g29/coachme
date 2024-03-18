<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>

<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a>
    <img src="https://velog.velcdn.com/images/lee02g29/post/cb5b3090-8f59-438d-8cfd-49959d5fb2ad/image.png" alt="Logo" width="220" height="80">
  </a>

<h1 align="center">Coach Me</h1>

  <h2 align="center">
    일상에서 코칭을 받을 수 있는 화상 플랫폼입니다.
    <br />
  </h2>
</div>

<!-- TABLE OF CONTENTS -->

## 목차

1. [프로젝트 개요](#1-프로젝트-개요)
2. [화면](#2-화면)
3. [프로젝트 구조](#3-프로젝트-구조)
4. [기술 스택](#4-기술-스택)
5. [팀원](#5-팀원)

<!-- 프로젝트 개요 -->

## 1. 프로젝트 개요

### 개발 기간

##### 2024/01/03 - 2024/02/15(7주)

### 기획의도

##### 전문가와 비전문가를 연결하여 서로의 니즈를 만족시키고, 이러한 과정에서 서비스 이용자들의 편의를 제공하기 위함

### 요약

##### 사용자가 시공간의 제약없이 본인이 필요한 서비스를 제공하고, 제공받을 수 있는 플랫폼을 제작

### 기능

1. 판매자는 소비자에게 유료 실시간 강의를 제공
2. 판매자는 소비자에게 유료 화상에 대한 녹화본을 제공
3. 판매자는 본인을 홍보하기 위한 영상과 유료 화상에 대한 녹화본을 편집하여 업로드
4. 소비자는 판매자를 직접 선정하여 컨택(1:1 채팅)할 수 있음
5. 소비자는 판매자의 라이브 강의에 직접 참여하면서 어려움을 해소할 수 있음
6. 소비자는 시간적 제약이나 장비의 부재 등으로 화상에 참여가 제한될 경우 녹화본을 시청할 수 있음

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- 화면 -->

## 2. 화면

### 메인 화면

![메인화면](https://github.com/lee02g29/coachme/assets/19562994/3152b9af-d0b5-4d61-b004-d81160fb6f00)

### 검색화면(코치)

#### 리스트

![코치검색페이지_리스트](https://github.com/lee02g29/coachme/assets/19562994/278fda3b-1f71-4849-9ceb-064d9bd94cc2)

#### 카드

![코치검색페이지_카드](https://github.com/lee02g29/coachme/assets/19562994/69bf67eb-8199-4ebb-b33b-b6dcb6730098)

### 검색화면(코칭)

![코칭검색페이지](https://github.com/lee02g29/coachme/assets/19562994/57dd1672-45f1-4d51-95a8-4d664dd97f6c)

### 마이페이지(코미)

![마이페이지1](https://github.com/lee02g29/coachme/assets/19562994/d14a7089-f3d2-427e-b084-98574737cb3a)

![마이페이지2](https://github.com/lee02g29/coachme/assets/19562994/ad848813-5959-41d0-9946-a2b05816d32e)

### 마이페이지(코치)

![코치페이지1](https://github.com/lee02g29/coachme/assets/19562994/c755b252-c279-4cd0-b2da-e1b7bd8e076c)

![코치페이지2](https://github.com/lee02g29/coachme/assets/19562994/c40e0f47-2bc4-427e-872d-bb06cbfdada0)

![코치페이지3](https://github.com/lee02g29/coachme/assets/19562994/28cbb84c-6666-43b8-8413-29f792c4fd48)

![코치페이지4](https://github.com/lee02g29/coachme/assets/19562994/8ee3708f-abed-4736-9709-aeb1c029ae5f)

### 코치 포트폴리오
영상으로 대체합니다. 현재는 스크롤형이 아닌, 라우터형으로 변경되었습니다.  
리뷰 CRUD 기능도 추가되었습니다.   
![코치 포트폴리오 API 연동](https://github.com/lee02g29/coachme/assets/19562994/88e1399d-e607-4f61-84e4-aaab2d11cb02)

### 코칭 상세페이지
영상으로 대체합니다. 현재는 스크롤형이 아닌, 라우터형으로 변경되었습니다.  
리뷰 CRUD 기능도 추가되었습니다.   
![코칭 상세페이지 API 영상](https://github.com/lee02g29/coachme/assets/19562994/f43c5c8e-05a6-4ab2-863f-24aaee32ea08)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- structure -->

## 3. 프로젝트 구조

### 아키텍처

![아키텍처](https://github.com/lee02g29/coachme/assets/19562994/83908158-a407-4bb6-8c35-ecdb20cb8777)

### 와이어 프레임

![와이어프레임](https://github.com/lee02g29/coachme/assets/19562994/29071401-e034-4ca4-aa27-e595e0e327c3)

### ERD

![live_coaching](https://github.com/lee02g29/coachme/assets/19562994/f0790655-4839-422d-a810-9b785a338d4f)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- 기술스택 -->

## 4. 기술 스택

### Language

![Java][Java] ![JavaScript][JavaScript] ![CSS3][CSS3] ![HTML5][HTML5] ![Python][Python]

### Cooperation

![git][git] ![gitlab][gitlab] ![Jira][Jira] ![jenkins][jenkins] ![mattermost][mattermost] ![kakaotalk][kakaotalk] ![discord][discord] ![figma][figma] ![notion][notion]

### Tools

![intellij][intellij] ![vscode][vscode] ![workbench][workbench]

### Framework & Library

![springboot][springboot] ![Vue][Vue.js] ![fastapi][fastapi] ![pinia][pinia]

### Infrastructure

![amazonec2][amazonec2] ![nginx][nginx] ![redis][redis] ![mysql][mysql] ![docker][docker] ![OpenVidu][OpenVidu] ![jenkins2][jenkins2]

### Others

![quasar][quasar]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- 팀원 -->

## 5. 팀원

#### \* 남상엽 - 팀장, 프론트엔드, 기획, 프로젝트 관리

#### \* 이혜지 - 프론트엔드, FE팀장, 컴포넌트 관리, Atomic Design

#### \* 김동현 - 프론트엔드, 회의록 관리, 레이아웃 설계, Wireframe 관리

#### \* 박민아 - 백엔드, 발표자, Database관리, API 관리

#### \* 이준학 - 백엔드, BE팀장, 인프라 관리, AI 연구

#### \* 김지원 - 백엔드, Jira 관리, Socket 및 WebRTC 통신

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[Java]: https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=java&logoColor=white
[JavaScript]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white
[CSS3]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white
[HTML5]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white
[Python]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white

[git]: https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white
[gitlab]: https://img.shields.io/badge/gitlab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white
[Jira]: https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jirasoftware&logoColor=white
[jenkins]: https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white
[mattermost]: https://img.shields.io/badge/mattermost-0058CC?style=for-the-badge&logo=mattermost&logoColor=white
[kakaotalk]: https://img.shields.io/badge/kakaotalk-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=white
[discord]: https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white
[figma]: https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white
[notion]: https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white

[intellij]: https://img.shields.io/badge/intellij-000000?style=for-the-badge&logo=intellijidea&logoColor=white
[vscode]: https://img.shields.io/badge/vscode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white
[workbench]: https://img.shields.io/badge/workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=white

[springboot]: https://img.shields.io/badge/springboot-v3.1-6DB33F?style=for-the-badge&logo=springboot&logoColor=white
[Vue.js]: https://img.shields.io/badge/Vue.js-v3.4.15-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[fastapi]: https://img.shields.io/badge/fastAPI-v0.109.0-009688?style=for-the-badge&logo=fastapi&logoColor=4FC08D
[pinia]: https://img.shields.io/badge/pinia-v2.1.7-FFF000?style=for-the-badge&logoColor=white

[amazonec2]: https://img.shields.io/badge/amazonec2-Ubuntu_20.04-FF9900?style=for-the-badge&logo=amazonec2&logoColor=4FC08D
[nginx]: https://img.shields.io/badge/nginx-v1.18.0-009639?style=for-the-badge&logo=nginx&logoColor=4FC08D
[redis]: https://img.shields.io/badge/redis-v5.0.7-DC382D?style=for-the-badge&logo=redis&logoColor=4FC08D
[mysql]: https://img.shields.io/badge/mysql-v8.0.36-4479A1?style=for-the-badge&logo=mysql&logoColor=white
[docker]: https://img.shields.io/badge/docker-v25.0.3-2496ED?style=for-the-badge&logo=docker&logoColor=white
[OpenVidu]: https://img.shields.io/badge/OpenVidu-v2.29.0-333333?style=for-the-badge&logo=webrtc&logoColor=white
[jenkins2]: https://img.shields.io/badge/jenkins-v2.441-D24939?style=for-the-badge&logo=jenkins&logoColor=white
[quasar]: https://img.shields.io/badge/quasar-v2.14.2-050A14?style=for-the-badge&logo=quasar&logoColor=white
