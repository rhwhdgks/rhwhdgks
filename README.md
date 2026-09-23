# Jonghan Ko

고려대학교 컴퓨터공학 전공 · 금융 데이터 분석과 거래 시스템 개발

시장 데이터를 분석하고, 거래 프로그램의 주문·위험 관리 기능을 개발합니다. 연구 결과, 시스템 운영 검증, 실제 거래 수익은 각각 구분해 기록합니다.

## 대표 프로젝트

- **[선물 거래 실행 엔진](https://github.com/rhwhdgks/funding-arb-engine)** — 바이낸스와 OKX 선물거래소의 주문·포지션을 함께 관리합니다. 한쪽 주문만 체결됐을 때 반대쪽 거래로 위험을 줄이고, 실패나 중단 뒤 남은 포지션을 확인·복구하는 경로를 구현했습니다. [자동 테스트 기록](https://github.com/rhwhdgks/funding-arb-engine/actions)

- **[코인 주문흐름 연구](https://github.com/rhwhdgks/crypto-order-flow-synchronization)** — 여러 코인의 매수·매도 체결이 함께 움직이는지 거래 자료와 호가 자료로 분석했습니다. 연구에 쓰지 않은 기간과 다른 거래소에서 다시 확인했고, 별도로 검토한 매매 아이디어는 거래비용을 고려하면 수익성을 확인하지 못했습니다.

- **[DART 공시 질의응답 API](https://github.com/rhwhdgks/mirae-asset-dart)** — Team dis-001과 함께 개발한 금융감독원 전자공시(DART) 질의응답 API의 공개 코드입니다. 질문에 맞는 공시의 기간·단위·정정 이력을 확인하고, 계산값과 원문 근거를 연결합니다.

- **[ETF 차트 이미지 연구](https://github.com/rhwhdgks/etf-image-alpha-ode)** — 가격 차트 이미지가 ETF 간 향후 수익률 순위를 예측하는 데 도움이 되는지 검토했습니다. 신호 후보와 ETF 간 움직임을 나타내는 위험 자료를 만들고, 과거 데이터만으로 예측하도록 검증했습니다.

- **[암호화폐 집단추종 지표 검증](https://github.com/rhwhdgks/crypto-herding-research)** — 코인 가격이 함께 움직인다는 이유만으로 투자자들이 서로 따라 거래했다고 볼 수 있는지 검토했습니다. 기존 논문 결과를 재현하고 가상시장 실험으로 지표 해석의 한계를 확인했습니다.

## 사용 기술과 활동

- **분석·개발:** Python, SQL, pandas, NumPy, SciPy, PyTorch
- **API·운영:** FastAPI, MariaDB, Linux
- **Find-A:** 2026년부터 퀀트 연구와 거래 시스템 프로젝트 참여
