<div align="center">
  <h1>PLAYONA</h1>
  <p><strong>플랫폼의 경계 없이, 음악으로 연결되는 경험</strong></p>
  <p>
    음악 링크 하나로 여러 스트리밍 플랫폼의 재생 링크를 자동 생성하고,<br/>
    사용자의 선호 플랫폼으로 자연스럽게 연결해주는 음악 공유 서비스입니다.
  </p>
  <p>
    <a href="https://playona-five.vercel.app/"><strong>Service Link</strong></a>
  </p>
</div>

---

## About PLAYONA

PLAYONA는 서로 다른 음악 플랫폼을 사용하는 사용자들이 더 쉽게 음악을 공유할 수 있도록 만든 서비스입니다.

기존에는 Spotify, Apple Music, YouTube Music, Melon, Genie, FLO 등 사용하는 플랫폼이 다르면 공유받은 링크가 바로 열리지 않거나, 같은 곡을 다시 검색해야 하는 불편함이 있었습니다.

PLAYONA는 하나의 음악 URL을 입력하면 여러 플랫폼의 직접 재생 링크를 자동으로 생성하고, 사용자가 선호하는 플랫폼으로 이동할 수 있도록 도와줍니다.

---

## Key Features

| Feature | Description |
| --- | --- |
| 통합 음악 링크 생성 | 하나의 음악 URL을 기반으로 여러 플랫폼 링크를 자동 생성합니다. |
| 크로스 플랫폼 매칭 | ISRC, 제목, 아티스트 정보를 기반으로 동일 곡을 다른 플랫폼에서 탐색합니다. |
| 선호 플랫폼 리다이렉트 | 로그인 사용자는 설정한 선호 플랫폼으로 자동 이동할 수 있습니다. |
| 비로그인 공유 지원 | 로그인 없이도 음악 공유 링크를 생성하고 접근할 수 있습니다. |
| 단축 URL 제공 | 공유하기 쉬운 짧은 링크를 생성합니다. |
| 캐싱 기반 최적화 | 이미 매칭된 곡 정보는 캐싱하여 반복 요청 효율을 높입니다. |

---

## Service Flow

```text
음악 URL 입력
   ↓
메타데이터 추출
   ↓
ISRC / 제목 / 아티스트 기반 플랫폼 매칭
   ↓
6개 플랫폼 직접 링크 생성
   ↓
단축 URL 생성
   ↓
사용자 선호 플랫폼 또는 선택 UI로 이동
```

---

## Demo

| 게스트 공유 링크 접근 | 브라우저 기억 기반 자동 리다이렉트 |
| --- | --- |
| <img src="https://nullisdefined.s3.ap-northeast-2.amazonaws.com/images/20e8785e2978a2c2f3c03acb7dcc9503.gif" alt="게스트 최초 공유 링크 접근 및 리다이렉트" width="400"/> | <img src="https://nullisdefined.s3.ap-northeast-2.amazonaws.com/images/a0b63cf25a07978dad9a709a4de76cb5.gif" alt="브라우저 기억 기반 자동 리다이렉트" width="400"/> |
| 공유 링크에 처음 접근한 사용자가 곡 정보를 확인하고 원하는 플랫폼으로 이동합니다. | 이전 선택 플랫폼을 브라우저에 기억해 다음 접근 시 자동으로 이동합니다. |

| 로그인 및 프로필 설정 |
| --- |
| <img src="https://nullisdefined.s3.ap-northeast-2.amazonaws.com/images/cf777625f733ff5a32757f9abfdcb0c4.gif" alt="로그인 및 프로필 설정" width="400"/> |
| 로그인 후 프로필과 선호 플랫폼을 설정하여 개인화된 리다이렉트 경험을 사용할 수 있습니다. |

| 통합 링크 히스토리 | 음악 링크 변환 및 공유 |
| --- | --- |
| <img src="https://nullisdefined.s3.ap-northeast-2.amazonaws.com/images/3528e71f9901fdc8b13fcf2de14b1d67.gif" alt="통합 링크 히스토리 확인" width="400"/> | <img src="https://nullisdefined.s3.ap-northeast-2.amazonaws.com/images/7ac2a26481b6e126b19cf6e7dfaa4fc7.gif" alt="음악 링크 변환 및 카카오톡 공유" width="400"/> |
| 생성한 통합 음악 링크를 히스토리에서 확인하고 다시 사용할 수 있습니다. | 음악 링크를 PLAYONA 통합 링크로 변환한 뒤 카카오톡으로 공유할 수 있습니다. |

---

## Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"/>
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT"/>
<img src="https://img.shields.io/badge/nanoid-000000?style=for-the-badge" alt="nanoid"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
<img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" alt="PWA"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" alt="AWS EC2"/>
<img src="https://img.shields.io/badge/AWS_RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white" alt="AWS RDS"/>
<img src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" alt="Amazon S3"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/>
<img src="https://img.shields.io/badge/Spotify_API-1DB954?style=for-the-badge&logo=spotify&logoColor=white" alt="Spotify API"/>
<img src="https://img.shields.io/badge/YouTube_API-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube API"/>
<img src="https://img.shields.io/badge/iTunes_Search_API-FA243C?style=for-the-badge&logo=applemusic&logoColor=white" alt="iTunes Search API"/>

</div>

---

## Platform Matching Strategy

PLAYONA는 플랫폼별 특성에 따라 서로 다른 방식으로 음악 정보를 매칭합니다.

| Platform | Strategy |
| --- | --- |
| Spotify | 공식 API를 통해 메타데이터와 ISRC를 추출합니다. |
| Apple Music | iTunes Search API를 활용해 곡 정보를 조회합니다. |
| YouTube Music | YouTube Data API v3와 Topic 채널 탐지를 활용합니다. |
| Melon / Genie / FLO | 공식 API가 제공되지 않아 HTTP 요청과 HTML 파싱을 활용합니다. |

ISRC가 존재하는 경우 이를 우선적으로 사용하며, 필요한 경우 제목과 아티스트 기반 유사도 매칭을 함께 사용합니다.

---

## Architecture

PLAYONA는 음악 공유 링크를 중심으로 사용자, 트랙, 플랫폼, 플랫폼별 트랙 링크를 관리합니다.

| Domain | Description |
| --- | --- |
| User | 사용자 정보와 플랫폼 선호 설정을 관리합니다. |
| Track | 공유 대상 음악의 메타데이터를 관리합니다. |
| Platform | Spotify, Apple Music, YouTube Music 등 지원 플랫폼 정보를 관리합니다. |
| Platform Track | 특정 트랙의 플랫폼별 재생 링크를 관리합니다. |
| Shared Link | 사용자가 생성한 단축 공유 링크를 관리합니다. |
| User Platform Preference | 사용자별 선호 플랫폼 우선순위를 관리합니다. |

---

## Repositories

| Repository | Description |
| --- | --- |
| **[backend](https://github.com/Database-teamproject/playona)** | Spring Boot 기반의 백엔드 API 서버입니다. |
| **[frontend](https://github.com/Database-teamproject/playona-FE)** | React, TypeScript, Vite 기반의 프론트엔드 웹 애플리케이션입니다. |

---

## Team

### Back-End

| <img src="https://github.com/yunsung65.png" width="150"> | <img src="https://github.com/ThuMyatHtoo29.png" width="150"> |
| :------------------------------------------------------: | :----------------------------------------------------------: |
|           [이윤성](https://github.com/yunsung65)            |      [Thu Myat Htoo](https://github.com/ThuMyatHtoo29)       |
|                        yunsung65                         |                        ThuMyatHtoo29                         |

### Front-End

| <img src="https://github.com/nullisdefined.png" width="150"> | <img src="https://github.com/juncheolShin.png" width="150"> |
| :----------------------------------------------------------: | :---------------------------------------------------------: |
|           [김재우](https://github.com/nullisdefined)            |           [신준철](https://github.com/juncheolShin)            |
|                        nullisdefined                         |                        juncheolShin                         |

---

<div align="center">
  <p><strong><a href="https://playona-five.vercel.app/">PLAYONA</a></strong></p>
  <p>플랫폼의 경계 없이, 음악으로 연결되는 경험</p>
</div>

