# OTTPlayer

**Your streaming sites, organized in one place — with TMDB and IMDb ratings where supported.**

OTTPlayer is a **free, non-commercial Windows desktop application** that brings your favorite streaming websites together in one interface.

On supported Netflix, TVING, and Coupang Play pages, OTTPlayer shows **TMDB and IMDb rating badges** alongside movies and TV shows, making it easier to decide what to watch.

**Project status:** Actively developed. The first public download is being prepared.

> **Language note:** This page is available in [English](#english) and [한국어](#한국어).

---

## English

### Features

- **Streaming in one place:** Access your favorite OTT services from a single desktop application.
- **TMDB & IMDb ratings:** See rating badges on supported Netflix, TVING, and Coupang Play pages.
- **Custom websites:** Add a website by entering its name and URL.
- **Customizable menu:** Enable or disable sites and change their display order.
- **Portable site settings:** Keep custom website information in the local `custom_sites.json` file.
- **Rating links:** Open supported rating detail pages in your default web browser.
- **Local rating cache:** Reuse previously fetched rating information where available.
- **Auto-hiding top menu:** Move the mouse pointer to the top edge of the OTTPlayer window to reveal the top menu.
- **Adjustable window transparency:** While the mouse pointer is over the top menu, scroll the mouse wheel to adjust the window's transparency.

### Rating Support

| Streaming service | Rating badges |
| --- | --- |
| Netflix | Supported on compatible pages |
| TVING | Supported on compatible pages |
| Coupang Play | Supported on compatible pages |
| User-added websites | Not automatically supported |

You can add other websites for convenient access. **Adding a website does not automatically enable rating badges for that website.** Newly added websites initially appear in the disabled-site list and can be enabled through menu settings.

Rating support may change when streaming websites update their layouts or behavior. Service availability also varies by country.

### Download & Installation

**The first public release is being prepared.** When available, download it from the [GitHub Releases page](https://github.com/earthhero333/OTTPlayer/releases).

**Portable package**

1. Download the portable ZIP file from Releases.
2. Extract **all** files to a folder of your choice.
3. Launch `OTTPlayer.exe` from the extracted folder.
4. Keep the extracted files together; do not move only the EXE.

**System requirements**

- Windows x64
- Internet connection for streaming services and online rating lookups
- [.NET 10 Windows Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) — required for framework-dependent builds; self-contained builds include the .NET runtime
- [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/consumer) — required if not already installed

Some streaming services may limit login or DRM-protected playback in embedded browsers. OTTPlayer does not bypass those restrictions.

### API Configuration

Certain rating features require you to enter your own **TMDB API Read Access Token** and, where applicable, an **OMDb API key**, in OTTPlayer.

- API credentials are **not included** with the distributed application.
- Do not share your keys or include them in screenshots, bug reports, or GitHub uploads.
- Rating availability depends on the relevant API and its usage terms.

### Privacy, Independence & Limitations

OTTPlayer does **not** provide, host, or distribute movies, TV shows, or streaming subscriptions. You access each streaming service through its own website and account, where required.

OTTPlayer is an independent, unofficial project. It is not affiliated with or endorsed by Netflix, TVING, Coupang Play, IMDb, TMDB, OMDb, or other streaming providers. All trademarks belong to their respective owners.

The application is currently distributed as a free, non-commercial project. **The source code is not currently published.**

### Feedback

Please use [GitHub Issues](https://github.com/earthhero333/OTTPlayer/issues) (when enabled) to report bugs, compatibility issues, or feature suggestions. Include the affected website, steps to reproduce the issue, and screenshots if helpful. **Never include passwords, personal tokens, or API keys.**

### Credits

Rating information may be retrieved from [The Movie Database (TMDB)](https://www.themoviedb.org/) and [OMDb API](https://www.omdbapi.com/), subject to their respective terms.

**This product uses the TMDB API but is not endorsed or certified by TMDB.**

---

## 한국어

**OTT 사이트를 한곳에서 관리하고, 지원되는 화면에서는 TMDB·IMDb 평점까지 확인하세요.**

OTTPlayer는 여러 스트리밍 웹사이트를 하나의 창에서 이용할 수 있도록 만든 **무료·비상업용 Windows 데스크톱 프로그램**입니다.

넷플릭스, 티빙, 쿠팡플레이의 지원 화면에서 영화·드라마 제목과 함께 **TMDB 및 IMDb 평점 배지**를 표시하여 작품 선택을 도와줍니다.

**개발 상태:** 지속 개발 중이며 첫 공개 배포를 준비하고 있습니다.

### 주요 기능

- **OTT 사이트 통합:** 여러 스트리밍 사이트를 하나의 프로그램에서 이용
- **평점 배지:** 넷플릭스·티빙·쿠팡플레이의 지원 화면에 TMDB·IMDb 평점 표시
- **사용자 사이트 추가:** 사이트 이름과 URL을 입력해 원하는 웹사이트 등록
- **메뉴 편집:** 사이트 활성화·비활성화 및 표시 순서 변경
- **설정 보관:** `custom_sites.json`에 사용자 지정 사이트 정보 로컬 저장
- **외부 상세 링크:** 지원되는 평점 상세 페이지를 Windows 기본 브라우저로 열기
- **로컬 평점 캐시:** 기존 조회 결과를 가능한 범위에서 재사용
- **자동 숨김 상단 메뉴:** OTTPlayer 창 맨 위쪽으로 마우스를 이동하면 상단 메뉴가 나타남
- **창 투명도 조절:** 상단 메뉴에 마우스를 올린 상태에서 마우스 휠을 돌려 창의 투명도를 조절

### 평점 지원 현황

| 사이트 | 평점 표시 |
| --- | --- |
| 넷플릭스 (Netflix) | 지원 화면에서 제공 |
| 티빙 (TVING) | 지원 화면에서 제공 |
| 쿠팡플레이 (Coupang Play) | 지원 화면에서 제공 |
| 사용자가 추가한 웹사이트 | 자동 지원 안 함 |

사용자 지정 사이트는 이름과 URL을 입력해 추가할 수 있습니다. **새로 등록한 사이트는 처음에 비활성화 목록에 들어가며, 메뉴 설정에서 활성화할 수 있습니다.** 사이트를 추가한다고 해서 평점 기능까지 자동으로 지원되는 것은 아닙니다.

OTT 사이트의 화면 구조가 변경되면 평점 표시가 일시적으로 동작하지 않을 수 있습니다. 서비스 제공 지역에 따라서도 이용 가능 여부가 달라질 수 있습니다.

### 다운로드 및 설치

**첫 공개 버전을 준비하고 있습니다.** 배포 파일이 올라오면 [GitHub Releases](https://github.com/earthhero333/OTTPlayer/releases)에서 다운로드할 수 있습니다.

**포터블 버전**

1. Releases에서 포터블 ZIP 파일을 다운로드합니다.
2. ZIP 파일을 원하는 폴더에 **모두 압축 해제**합니다.
3. 압축을 해제한 폴더에서 `OTTPlayer.exe`를 실행합니다.
4. EXE 파일만 따로 옮기지 말고 나머지 구성 파일도 함께 보관합니다.

**시스템 요구사항**

- Windows 64비트(x64)
- OTT 접속 및 온라인 평점 조회를 위한 인터넷 연결
- [.NET 10 Windows Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) — 런타임 미포함 배포본에 필요하며, 자체 포함형 배포본에는 .NET 런타임이 포함됨
- [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/consumer) — 설치되어 있지 않은 경우 필요

일부 OTT 서비스에서는 내장 브라우저 로그인이나 DRM 보호 영상의 재생이 제한될 수 있으며, OTTPlayer는 이러한 제한을 우회하지 않습니다.

### API 설정

일부 평점 기능에는 사용자가 직접 발급받은 **TMDB API Read Access Token**과, 해당하는 경우 **OMDb API 키**가 필요합니다. 프로그램 내 설정 화면에서 각자의 인증정보를 입력해 주세요.

- 배포 프로그램에 사용자별 API 토큰이나 키를 포함하지 않습니다.
- 토큰·API 키를 다른 사람에게 공유하거나 GitHub 및 오류 제보에 첨부하지 마세요.
- 평점 제공 범위는 각 API의 정책과 제공 상태에 영향을 받습니다.

### 개인정보·비공식 프로그램 안내

OTTPlayer는 OTT 영상, 콘텐츠 파일 또는 구독권을 직접 제공하지 않습니다. 각 OTT 서비스의 웹사이트와 사용자 계정을 이용합니다.

OTTPlayer는 독립적으로 개발하는 **비공식 프로그램**이며 넷플릭스, 티빙, 쿠팡플레이, IMDb, TMDB, OMDb 등의 공식 앱이거나 제휴·승인을 받은 서비스가 아닙니다. 각 상표의 권리는 해당 소유자에게 있습니다.

현재 **무료·비상업용**으로 개발 및 배포를 준비하고 있으며, **소스 코드는 공개하지 않고 있습니다.**

### 오류 제보 및 개선 제안

문제점이나 아이디어가 있으면 [GitHub Issues](https://github.com/earthhero333/OTTPlayer/issues)가 활성화된 경우 해당 메뉴로 알려주세요. 발생 사이트, 재현 순서, 관련 스크린샷을 함께 보내면 도움이 됩니다. **비밀번호, 개인 토큰, API 키는 절대 포함하지 마세요.**

### 데이터 출처

평점 정보는 각 서비스의 이용 조건에 따라 [TMDB](https://www.themoviedb.org/) 및 [OMDb API](https://www.omdbapi.com/) 등을 통해 제공될 수 있습니다.

**본 프로그램은 TMDB API를 사용하지만 TMDB의 승인 또는 인증을 받은 제품이 아닙니다.**

---

**OTTPlayer — Browse, Discover, and Check Ratings.**
