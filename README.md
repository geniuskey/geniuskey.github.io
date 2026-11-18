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
| Glossary | [/glossary](https://pages.euiyun.com/glossary/) | 한/영 조직용 셀프호스팅 용어집 관리 플랫폼 |
| Korea Privacy Dev Guide | [/privacy-guide](https://pages.euiyun.com/privacy-guide/) | 개발자를 위한 개인정보 보호·정보보안 실무 가이드 |
| Mac 가격 비교 | [/mac-prices](https://pages.euiyun.com/mac-prices/) | M1 이후 Mac 전 모델 한국 정가 비교 |
| AI-Ready Data | [/AI-Ready-Data](https://pages.euiyun.com/AI-Ready-Data/) | Data Ready + Knowledge Ready 준비도 진단과 90일 로드맵 |
| MemoCast | [/MemoCast](https://pages.euiyun.com/MemoCast/) | DRAM/NAND/HBM 메모리 수요 예측 위키와 시뮬레이터 |
| BPMN Flow | [/bpmn-flow](https://pages.euiyun.com/bpmn-flow/) | 브라우저 기반 BPMN 2.0 에디터 및 프로세스 분석기 |

## 구조

- `index.html` — 허브 페이지 (단일 파일, 빌드 없음)
- `assets/img/` — 프로젝트 썸네일(1200x630 webp), OG 이미지
- `sitemap.xml`, `robots.txt` — SEO
- `CNAME` — `pages.euiyun.com`

## 프로젝트 추가

1. `assets/img/<slug>.webp` 썸네일 추가 (1200x630)
2. `index.html`의 `#projects` 그리드에 카드 추가, JSON-LD `hasPart`와 meta description, 프로젝트 수 갱신
3. `sitemap.xml`에 URL 추가 (프로젝트 자체 sitemap이 있으면 `robots.txt`에 추가)
