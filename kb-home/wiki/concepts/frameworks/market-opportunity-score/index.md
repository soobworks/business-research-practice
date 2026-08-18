# 기회점수 — AOS·DOS

## AOS (Adjusted Opportunity Score)

전통적 OS(=Importance×2−Satisfaction)는 Importance가 두 번 반영되는 결함이 있다. **AOS = Importance × (1 − Satisfaction/5)** 는 불만족을 비율로 먼저 만들어 이 결함을 없앤다.

## DOS (Discovered Opportunity Score)

AOS에 시장 규모를 곱해 "발견된 기회"를 만든다. **DOS = (Importance − Satisfaction) × Market Relevance(MR)**.

**이 프로젝트가 발견/수정한 규칙**: ① **MR은 Pain별이 아니라 인물(페르소나)별로 부여한다** — Pain별로 매기면 Importance를 두 번 세는 것과 같은 결함이 재발한다(1인가구-한끼라우터 케이스에서 최초 버전의 오류를 발견하고 전면 재작성한 이력, [decisions](../../../decisions/index.md) 참고). ② **모수(TAM/SAM/SOM)는 인과가 끊기지 않는 것을 고른다** — TAM은 너무 넓어 MR이 전부 0에 수렴하므로 SAM을 기본으로 쓴다. ③ **SAM(확장성)과 SOM(1년차 실행)을 병기**해 "지금 검증할 것"과 "커지려면 필요한 것"을 구분한다.

## 사분면 기준선 세 가지 방식

| 방식 | 기준 | 이 프로젝트의 선택 |
| --- | --- | --- |
| A. 척도 중간값(3.0 고정) | Likert 5점 중앙 | 미채택 — 데이터가 몰리면 상하 구분이 무의미해짐 |
| B. 평균 + 0.5σ | 실제 데이터 분포 | AOS 기회경계(2.09) 산출에 사용 |
| C. 중앙값 | 실제 데이터 분포 | **사분면 배치(Imp 4.0·Sat 3.0)에 채택** — 정수 척도에 값이 몰릴 때 평균보다 밀집 구간을 더 정확히 반영 |

## 케이스 적용

[1인가구-한끼라우터](../../../cases/1인가구-한끼라우터/aos-dos.md) — 32개 Pain, AOS×DOS 혼합매트릭스(X=AOS·Y=DOS).

## 근거 등급

계산식·모수선택 원칙은 **(확인, 이번 프로젝트에서 확정한 규칙)**. 실제 Imp·Sat·MR 값은 **(가정)**.
