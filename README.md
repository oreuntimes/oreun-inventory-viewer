# OREUN INVENTORY Viewer

오른인벤토리 공개 뷰어 전용 저장소입니다.

이 저장소는 외부 공유용 결과물만 담습니다. 원본 작업 레포의 프롬프트, 스키마, 검증 스크립트, 운영 문서는 포함하지 않습니다.

## 공개 링크

- 전체 목록: https://oreuntimes.github.io/oreun-inventory-viewer/
- 해성디에스 예시: https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=195870

## 종목 목록

| 코드 | 종목명 | 공개 뷰어 |
|---|---|---|
| 004710 | 한솔테크닉스 | https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=004710 |
| 005620 | 남화토건 | https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=005620 |
| 001210 | 금호전기 | https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=001210 |
| 002990 | 금호건설 | https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=002990 |
| 228340 | 동양파일 | https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=228340 |
| 195870 | 해성디에스 | https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=195870 |
| 089030 | 테크윙 | https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=089030 |
| 073240 | 금호타이어 | https://oreuntimes.github.io/oreun-inventory-viewer/viewer/stock.html?code=073240 |

## 공개 포함 범위

- `viewer/`: 공통 HTML 뷰어
- `stocks/`: 공개 가능한 종목별 JSON 결과물
- `stocks/_index.json`: 종목코드와 JSON 파일명 매핑

주의: 이 뷰어는 브라우저에서 JSON을 직접 읽습니다. 따라서 `stocks/*.json`에 들어 있는 내용은 공개 데이터로 취급해야 합니다.
