# 👨‍💻 사내 T.M.S 서비스 Tickety.

- 배포 URL :   [tickety.kr](http://-/)

<br>

## 프로젝트 소개

- Tickety는 사내 팀 내, 야호야호 야야호
- **가나다의 기능**: 가나다.

<br>

## 팀원 구성

| **PM/BE** | **PL/FE** | **PL/BE** |
| :------: | :------: | :------: | 
| **김민서(Phurray)** | **한상결(Terry)** | **김지원(Wonee)** |
| [<img src="https://avatars.githubusercontent.com/hurrayPersimmon" height=150 width=150> <br/> @hurrayPersimmon](https://github.com/hurrayPersimmon) | [<img src="https://avatars.githubusercontent.com/sanggyeol1" height=150 width=150> <br/> @sanggyeol1](https://github.com/sanggyeol1) | [<img src="https://avatars.githubusercontent.com/kiwijomn" height=150 width=150> <br/> @kiwijomn](https://github.com/kiwijomn) |

| **FE** | **INFRA** | **BE** | **BE** | **BE** | **BE** |
| :------: | :------: | :------: | :------: | :------: | :------: |
| **최예원(Loopy)** | **박정재(Harrison)** | **강수진(Curi)** | **김민형(Thama)** | **박선웅(Tomcat)** | **하재웅(Yosbi)** |
| [<img src="https://avatars.githubusercontent.com/yeonge2" height=150 width=150> <br/> @yeonge2](https://github.com/yeonge2) | [<img src="https://avatars.githubusercontent.com/j-ash0224" height=150 width=150> <br/> @j-ash0224](https://github.com/j-ash0224) | [<img src="https://avatars.githubusercontent.com/1214sujin" height=150 width=150> <br/> @1214sujin](https://github.com/1214sujin) | [<img src="https://avatars.githubusercontent.com/strongmhk" height=150 width=150> <br/> @strongmhk](https://github.com/strongmhk) | [<img src="https://avatars.githubusercontent.com/SWPark0506" height=150 width=150> <br/> @SWPark0506](https://github.com/SWPark0506) | [<img src="https://avatars.githubusercontent.com/qlfyd123" height=150 width=150> <br/> @qlfyd123](https://github.com/qlfyd123) |
<br>

## 1. 개발 환경
- Frontend : Next.js, React,
- Backend : Java, Spring
- Infrastructure : Xen Orchestra, Docker, KaKaoCloud
- Database : MySQL, Redis
- CI/CD : Github, Jenkins
- 협업 툴 : Notion, Jira, Github, Slack, SpreadSheet
- 서비스 배포 환경: On-premises, Kubenetes
- 디자인 : Figma

<br>

## 2. 채택한 개발 기술과 브랜치 전략

### Next.js
- SEO 최적화와 성능 향상이 중요한 요구사항이었기 때문에, **Next.js**를 선택했습니다.
- Next.js는 서버 사이드 렌더링(SSR)과 정적 사이트 생성(SSG)을 기본적으로 지원하여, 검색 엔진 최적화(SEO)와 빠른 로딩 속도를 동시에 만족시킬 수 있었습니다.
- 또한, 페이지 기반 라우팅, API 라우트 지원 등 생산성을 높이는 다양한 기능을 제공하여 개발 시간을 단축시킬 수 있었습니다.

### React
- UI 구축의 효율성과 코드의 재사용성을 고려하여 **React**를 선택했습니다.
- React는 컴포넌트 기반의 설계를 통해 복잡한 사용자 인터페이스를 쉽게 관리할 수 있도록 도와줍니다.
- 또한, React의 가상 DOM을 활용해 성능을 최적화할 수 있어 사용자 경험을 향상시키는 데 큰 도움이 되었습니다.

### SpringBoot
- 프로젝트의 규모와 복잡성을 고려해 **SpringBoot**를 채택했습니다.
- 

### 브랜치 전략
브랜치 전략은 **Git Flow**를 기반으로 설정하여, 각 브랜치가 명확한 역할을 갖도록 했습니다. 이 전략은 협업 시 효율적인 작업 분담과 코드 통합을 가능하게 했습니다

- **main**: 배포 환경에 최적화된 안정적인 코드만을 관리하기 위해 main 브랜치를 배포 단계에서만 사용했습니다.
- **develop**: develop 브랜치는 개발 단계에서 Git Flow의 master 역할을 하며, 모든 기능이 통합되는 주요 브랜치로 설정했습니다. 기능 개발이 완료되면 각 feature 브랜치에서 develop 브랜치로 병합하여 전체 프로젝트의 통합 상태를 관리했습니다.
- **feature**: 각 기능 단위로 독립적인 개발을 진행하기 위해 feature 브랜치를 사용했습니다. 이를 통해 다른 기능 개발에 영향을 미치지 않고 독립적으로 작업할 수 있었으며, 기능 개발이 완료되면 develop 브랜치에 병합하고, 병합 후에는 feature 브랜치를 삭제하여 깔끔한 브랜치 관리를 할 수 있었습니다.

<br>

## 4. 개발 기간 및 작업 관리

### 개발 기간

- 기획 : 2025-01-06 ~ 2025-01-17
- 전체 개발 기간 : 2025-01-18 ~ 2025-02-13
- QA 및 검증 : 2025-02-14 ~ 2025-02-18

<br>
