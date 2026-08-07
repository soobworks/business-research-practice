# TAM 딥리서치: 금융데이터 기반 개인 맞춤형 자산관리 서비스

> [분석 단위](../porters-five-forces/porters-five-forces-analysis-personal-asset-management.md): 마이데이터 기반으로 개인 자산 현황을 분석하고 맞춤형 자산배분·금융상품을 추천하는 핀테크 플랫폼. TAM은 이 정의를 만족하는 가장 넓은 상위 시장부터 잡는다 (1인 가구 등 세그먼트 필터링은 SAM 단계에서 진행).

## 1. TAM을 어느 층위로 잡을지부터 정한다

이 서비스는 두 개의 서로 다른 상위 시장에 걸쳐 있어, TAM을 하나로 확정하기 전에 층위를 구분해야 한다.

| 층위 | 정의 | 이 서비스와의 관계 |
| --- | --- | --- |
| **넓은 층위 — 개인 재무관리 앱(Personal Finance App) 시장** | 예산관리·지출추적 등 무료 조회 기능 중심 | 우리 서비스의 "무료 이용자" 진입점과 대응 |
| **좁은 층위 — 로보어드바이저(디지털 자산관리·투자자문) 시장** | 실제 자산배분·투자자문·상품가입까지 수행 | 우리 서비스의 "유료·AUM 고객" 수익화 지점과 대응 |

**주의(방법론적 함정)**: 로보어드바이저 시장 규모로 보도되는 수치는 대부분 **매출액이 아니라 관리자산총액(AUM)**이다. AUM은 수수료율(통상 연 0.2~1%)을 곱해야 실제 매출 기반 TAM으로 환산되므로, 두 개념을 섞으면 TAM이 수십~수백 배 부풀려진다.

## 2. 글로벌 시장 규모

- **개인 재무관리 앱 시장**: 2025년 약 USD 31.7B~32.3B 수준이라는 추정과, USD 165.9B에 달한다는 추정이 동시에 존재한다 — 후자는 재무관리 기능이 포함된 모든 핀테크 앱(결제·송금 포함)까지 넓게 잡은 것으로 보여, 정의가 다르면 5배 이상 차이가 난다는 점 자체가 리서치 결과다.
- **AI 기반 개인 자산관리 플랫폼**: 2025년 약 USD 9.8B, 2034년 USD 62.4B 전망 (CAGR 22.6%) — 우리 서비스(마이데이터+AI 추천)와 정의가 가장 가깝다.
- **로보어드바이저(AUM 관점)**: 2025년 추정치가 리서치사별로 USD 10.86B~27.34B로 3배 가까이 벌어진다 — "로보어드바이저"의 범위를 순수 자동화 자문만으로 보는지, 하이브리드(사람+AI) 자문까지 포함하는지에 따라 갈린다.

## 3. 국내 시장 규모

- 국내 로보어드바이저 관리자산 규모는 2018년 약 1조원 → 2020년 약 5조원 → **2025년 약 30조원**에 이를 것이라는 전망이 있다 (KEB하나은행, 2018년 추정 / Statista 인용). **이 추정치는 2018년에 만들어진 예측**이라는 점에 유의해야 한다 — 실제 2025년 수치와의 괴리 가능성을 SAM 단계에서 최신 데이터로 재검증할 필요가 있다.
- 참고 지표: 로보어드바이저 투자계약자 수는 2017년 3.8만 명 → 2020년 27.8만 명(약 620% 증가), 운용금액은 4,219억원 → 1조 4천억원(약 250% 증가) — 계약자 수 증가폭이 운용금액 증가폭보다 훨씬 커서, **1인당 위탁 금액은 오히려 작아지는 추세**로 읽힌다. 이는 "소액·다수" 고객 구조로 가고 있다는 뜻이며, SAM/SOM 단계에서 목표 고객 단가를 보수적으로 잡아야 한다는 시사점을 준다.
- 마이데이터 자체의 별도 시장 규모 통계는 검색 범위 내에서 찾지 못했다 — 마이데이터는 시장이라기보다 이 서비스들이 공통으로 쓰는 인프라(투입자원)에 가깝기 때문으로 보인다. TAM을 마이데이터 시장으로 잡는 것은 범주 오류다.

## 4. TAM 확정 (이 분석에서 채택하는 정의)

| 구분 | 채택 값 | 근거 |
| --- | --- | --- |
| 글로벌 TAM | **AI 기반 개인 자산관리 플랫폼 시장, 2025년 약 USD 9.8B** | 우리 서비스(마이데이터+AI 추천+상품연계)와 정의 범위가 가장 근접 |
| 국내 TAM | **로보어드바이저 관리자산 약 30조원(2025년 전망치, 매출 환산 시 수수료율 0.5% 가정 약 1,500억원 내외)** | AUM과 매출을 구분해 명시 — 실제 매출 기반 시장은 AUM보다 두 자릿수 작음 |

⚠️ 두 수치 모두 **재검증이 필요한 추정치**다 — 국내 수치는 2018년 예측이고, 글로벌 수치는 리서치사별 최대 5배 차이가 나는 항목 중 하나를 선택한 것이다. SAM 산정 시 최신 연차보고서·금감원 통계로 교차검증을 권장한다.

## Sources
- [Robo Advisory Market Size, Share, Trends | Growth Report, 2034 – Fortune Business Insights](https://www.fortunebusinessinsights.com/robo-advisory-market-109986)
- [Robo-Advisor Market Size Share & Forecast to 2035 – Global Growth Insights](https://www.globalgrowthinsights.com/market-reports/robo-advisor-market-101915)
- [Robo Advisory Market Report 2026 – Research and Markets](https://www.researchandmarkets.com/reports/5766552/robo-advisory-market-report)
- [디지털 금융혁신 : 로보 어드바이저(Robo Advisor) 서비스 동향 – SPRi](https://spri.kr/posts/view/16733?code=data_all&study_type=&board_type=industry_trend)
- [연구보고서 21-05 국내 로보어드바이저 현황과 성과 분석 – 자본시장연구원(KCMI)](https://www.kcmi.re.kr/kcmifile/report_data/1471/reportpdf_1471_1.pdf)
- [자산관리 대중화를 선도하는 로보어드바이저의 진화 – KDI 경제교육·정보센터](https://eiec.kdi.re.kr/policy/domesticView.do?ac=0000165823)
- [Personal Finance Management Market Size | CAGR of 7.2% – market.us](https://market.us/report/personal-finance-management-market/)
- [AI Personal Finance and Wealth Management Platform Market Research Report 2034 – marketintelo](https://marketintelo.com/report/ai-personal-finance-and-wealth-management-platform-market)
- [Personal Finance Apps Market Report: Size, Growth, Trends & Forecast (2025–2033) – Verified Market Research](https://www.verifiedmarketresearch.com/product/personal-finance-apps-market/)
