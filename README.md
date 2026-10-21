# Mining Dashboard

채굴기(마이너) 가동 상태와 채굴 풀(pool) 수익을 모니터링하는 대시보드.

## 구성
- `index.html` — 대시보드 페이지. 채굴 풀(dxpool, ckpool 등) API와 자체 백엔드(`kgu3405.tplinkdns.com` / `kgu3405.duckdns.org`)를 호출해 해시레이트, 수익 등 채굴 상태를 표시
- `favicon.svg`

## 동작 방식
외부 풀 API + 로컬 서버 데이터를 조합해서 주기적으로 갱신. 세부 지표 항목은 `index.html` 스크립트에서 확인 가능.
