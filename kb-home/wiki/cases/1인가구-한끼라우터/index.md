# 케이스: 1인가구 한 끼 해결 — 한끼라우터

> 이 프로젝트의 심화 케이스. 01~08 챕터 전체가 이 하나의 사업 아이디어에 순차적으로 적용됐다. 원본 소스: 프로젝트 루트 `01.porters-five-forces/`~`08.competitor-branding/`.

## 한 문단 정의

혼자 사는 사람이 오늘 가진 예산·시간 안에서 배달·포장·편의점-HMR 중 가장 납득되는 한 끼를 빠르게 고르도록 돕는 의사결정 지원 서비스. 주문·결제·배차는 하지 않는다. 제품 엔티티: [한끼라우터](../../entities/products-services/한끼라우터.md).

## 여정 지도 (프레임워크 적용 순서)

| 단계 | 페이지 | 핵심 결론 |
| --- | --- | --- |
| 1 | [Five Forces](./five-forces.md) | 산업 매력도 낮음(이중 비용압박형 과밀), 1인가구 근거리 니치는 예외 |
| 2 | [Value Chain](./value-chain.md) | 라이더(투입)와 배송(산출)이 "사람의 이동"이라는 동일 자원에 수렴 |
| 3 | [KSF](./ksf.md) | 니치 우선공략이 나머지 4개 KSF를 성립시키는 전제 |
| 4 | [TAM-SAM-SOM](./tam-sam-som.md) | SAM 9.02조원(bottom-up 확정), SOM 3.1만 가구 |
| 5 | [페르소나·CJM](./persona-cjm.md) | 12종 페르소나, 병목은 ③후보비교·①오늘의갈등 |
| 6 | [AOS·DOS](./aos-dos.md) | C1·C3의 즉시확정·지출가시화가 최우선 |
| 7 | [JTBD](./jtbd.md) | C1·C3·A2 모의 인터뷰, C5 대표성 리스크 발견 |
| 8 | [경쟁분석](./competitor-branding.md) | 6개사 실사, 채널통합형 의사결정 지원은 아무도 안 함 |
| 9 | [Value Proposition](./value-proposition.md) | 마스터 선언 + 4기둥(신뢰·방법·범위·통제) |

## 이 케이스에서 나온 교차 참조

- 등장 기업: [배달의민족](../../entities/companies/배달의민족.md)·[쿠팡이츠](../../entities/companies/쿠팡이츠.md)·[요기요](../../entities/companies/요기요.md)·[두잇](../../entities/companies/두잇.md)·[배달핏](../../entities/companies/배달핏.md)·[GS25](../../entities/companies/gs25.md)
- 등장 페르소나: [entities/personas](../../entities/personas/index.md) 12종 전체
- 관련 종합: [니치 집중 전략 반복](../../syntheses/니치-집중-전략-반복.md)
- 관련 의사결정: [decisions](../../decisions/index.md)
- 관련 미해결 질문: [open-questions](../../open-questions/index.md)

## 근거 등급

프레임워크 적용·수치 검증은 챕터별로 다르다 — 각 하위 페이지의 근거 등급 참고. 04~09챕터(SRS 이후)가 가장 견고하고(확인/근사 다수), 05~07챕터(페르소나·JTBD)는 전량 (가정) 등급이다.
