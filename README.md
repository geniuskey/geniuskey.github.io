# Euiyun Pages

[pages.euiyun.com](https://pages.euiyun.com/) 허브 페이지. `geniuskey/*` 저장소의 GitHub Pages 프로젝트들을 한곳에 모아 보여줍니다.

## Projects

| 프로젝트 | 경로 | 설명 |
| --- | --- | --- |
| IC Studio | [/ic-studio](https://pages.euiyun.com/ic-studio/) | 오픈소스 풀커스텀 IC 설계 환경 (회로도, SPICE, 레이아웃, DRC/LVS) |
| klayout-draw-mcp | [/klayout-draw-mcp](https://pages.euiyun.com/klayout-draw-mcp/) | AI 에이전트가 KLayout으로 GDS를 그리게 해주는 MCP 서버 |
| COMPASS | [/compass](https://pages.euiyun.com/compass/) | 9개 EM 솔버로 교차 검증하는 이미지 센서 광학 시뮬레이션 플랫폼 |
| PLAYPICK | [/lottery](https://pages.euiyun.com/lottery/) | 21가지 추첨 게임 |
| Geniuskey Arcade | [/arcade](https://pages.euiyun.com/arcade/) | 설치 없이 즐기는 22개 브라우저 게임 |
| trofeo-lcd | [/trofeo-lcd](https://pages.euiyun.com/trofeo-lcd/) | Thermalright Trofeo Vision 9.16" LCD용 PC 상태 + Claude/Codex 사용량 대시보드 |
| Ulanzi Lite | [/ulanzi-d200x](https://pages.euiyun.com/ulanzi-d200x/) | Ulanzi D200X용 포터블 Windows 컨트롤러 (단축키, 오디오, AI 사용량) |

## 구조

- `index.html` — 허브 페이지 (단일 파일, 빌드 없음)
- `assets/img/` — 프로젝트 썸네일(1200x630 webp), OG 이미지
- `sitemap.xml`, `robots.txt` — SEO
- `CNAME` — `pages.euiyun.com`

## 프로젝트 추가

1. `assets/img/<slug>.webp` 썸네일 추가 (1200x630)
2. `index.html`의 `#projects` 그리드에 카드 추가, JSON-LD `hasPart`와 meta description, 프로젝트 수 갱신
3. `sitemap.xml`에 URL 추가 (프로젝트 자체 sitemap이 있으면 `robots.txt`에 추가)
