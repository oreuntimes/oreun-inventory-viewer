# OREUN INVENTORY Viewer

오른인벤토리 공개 뷰어 전용 저장소입니다.

이 저장소는 외부 공유용 결과물만 담습니다. 원본 작업 레포의 프롬프트, 스키마, 검증 스크립트, 운영 문서는 포함하지 않습니다.

## 보기

- 목록: `viewer/index.html`
- 종목 상세: `viewer/stock.html?code=195870`

GitHub Pages 배포 후:

- `https://oreuntimes.github.io/oreun-inventory-viewer/`
- `https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=195870`

## 공개 포함 범위

- `viewer/`: 공통 HTML 뷰어
- `stocks/`: 공개 가능한 종목별 JSON 결과물
- `stocks/_index.json`: 종목코드와 JSON 파일명 매핑

주의: 이 뷰어는 브라우저에서 JSON을 직접 읽습니다. 따라서 `stocks/*.json`에 들어 있는 내용은 공개 데이터로 취급해야 합니다.
