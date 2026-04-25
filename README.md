# Lotte Members Customer Analytics

롯데멤버스 L.POINT 고객 데이터를 활용해 고객 행동을 분석하고, 재방문 가능성 모델링과 고객군별 마케팅 전략 제안으로 연결한 경진대회 프로젝트입니다.

## Overview

| 항목 | 내용 |
| --- | --- |
| 대회 | 제7회 롯데멤버스 빅데이터 경진대회 |
| 기간 | 2022.06.20 ~ 2022.08.12 |
| 주최/주관 | 롯데멤버스 |
| 팀 구성 | 3인팀, 팀원 |
| 결과 | 예선 탈락 |
| 주제 | L.POINT 고객 행동 분석 및 마케팅 전략 제안 |

## Approach

- 고객 기본 정보, 구매 이력, 제휴사 이용, L.PAY 이용 데이터를 결합해 분석용 피처를 생성했습니다.
- 구매 주기, 채널, 상품군, 결제 행동을 기반으로 고객 행동 패턴을 정리했습니다.
- 재방문 가능성 예측을 위해 LightGBM, CatBoost, Random Forest, DNN 등 여러 모델을 실험했습니다.
- 모델 예측과 군집화 결과를 바탕으로 고객군별 마케팅 전략을 제안했습니다.

## Repository Structure

```text
.
├── notebooks/
│   ├── 01_data_preprocessing_and_feature_engineering.ipynb
│   ├── 02_modeling.ipynb
│   └── 03_strategy_recommendation.ipynb
├── reports/
│   └── lotte_members_customer_analytics_report.pdf
├── requirements.txt
└── README.md
```

## Public Scope

이 저장소는 포트폴리오 공개용으로 정리한 버전입니다.

- 대회 제공 원본 데이터, 외부 데이터, 학습된 모델 파일, 제출 CSV는 포함하지 않았습니다.
- 노트북 출력 결과와 실행 메타데이터는 제거했습니다.
- 실행하려면 대회 데이터와 외부 데이터를 `data/` 경로에 별도로 배치해야 합니다.
