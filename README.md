# 롯데멤버스 고객 행동 분석

L.POINT 고객 데이터를 활용해 고객 행동을 분석하고 재방문 가능성 모델링과 마케팅 전략 제안으로 연결한 경진대회 프로젝트입니다.

## 개요

| 항목 | 내용 |
| --- | --- |
| 대회 | 제7회 롯데멤버스 빅데이터 경진대회 |
| 기간 | 2022.06.20 - 2022.08.12 |
| 주최 / 주관 | 롯데멤버스 / 롯데멤버스 |
| 결과 | 예선 탈락 |
| 주제 | L.POINT 고객 행동 분석 및 마케팅 전략 제안 |

## 접근

- 고객 기본 정보, 구매 이력, 제휴사 이용, L.PAY 데이터를 결합했습니다.
- 구매 주기, 채널, 상품군, 결제 행동 기반 피처를 구성했습니다.
- LightGBM, CatBoost, Random Forest, DNN 등 여러 모델로 재방문 가능성을 실험했습니다.
- 모델 예측과 고객군 분석을 바탕으로 마케팅 전략을 제안했습니다.

## 저장소 구성

```text
.
├── notebooks/
│   ├── 01_data_preprocessing_and_feature_engineering.ipynb
│   ├── 02_modeling.ipynb
│   └── 03_strategy_recommendation.ipynb
├── reports/
│   └── lotte_members_customer_analytics_report.pdf
└── requirements.txt
```

## 공개 범위

대회 원본 데이터, 외부 데이터, 모델 파일, 생성 산출물은 포함하지 않았습니다. 노트북 출력과 실행 메타데이터를 정리했습니다.
