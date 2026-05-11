---
layout: default
title: Seoul Apartment Price Factor Analysis
permalink: /projects/seoul-apartment/
---

<div class="project-header">
  <div class="eyebrow">Public Data · XGBoost · GAM · Model Interpretation</div>

  # Seoul Apartment Price Factor Analysis

  XGBoost와 GAM을 활용해 서울시 아파트 공시가격 변화율과 실거래가격의 영향 요인을 분석한 프로젝트입니다.
</div>

## Summary

| 항목 | 내용 |
|---|---|
| 목적 | 서울시 아파트 가격 변동 요인 분석과 예측 |
| 방법 | XGBoost, GAM, SHAP, Geocoding |
| 데이터 | 단지 정보, 가격 데이터, 인구통계, 인프라, 지형, 거시경제 지표 |
| 링크 | [GitHub Repository](https://github.com/Mizrhan/Analaysis_Seoul_Apartment) |

## Problem

주택 가격은 단일 요인으로 설명하기 어렵습니다.  
이 프로젝트는 공시가격 변화율과 실거래가격에 영향을 주는 복합 요인을 분석하고, 가격대별로 어떤 특성이 다르게 작동하는지 확인했습니다.

## My Role / Contribution

- 공공/외부 데이터 결합 구조 정리
- 주소 기반 Geocoding을 통한 공간 정보 결합
- 결측치와 이상치 처리
- XGBoost 기반 공시가격 변화율 예측
- GAM 기반 실거래가격 예측과 비선형 관계 해석
- SHAP 기반 주요 변수 해석

## Key Findings

- 공시가격 변화율에는 단지 규모와 물리적 특성이 중요하게 나타났습니다.
- 실거래가격에서는 인구 구조, 생활 편의성, 자산 가치 성격이 가격대별로 다르게 작동했습니다.
- 교통 인프라, 특히 차량 접근성은 두 모델에서 공통적으로 중요한 요인으로 확인되었습니다.

## Limitations

- 일부 데이터는 라이선스 문제로 저장소에 포함되지 않습니다.
- 공공 데이터의 기준 시점과 수집 방식 차이가 있어 해석 시 주의가 필요합니다.

## Portfolio Note

이 프로젝트는 공공 데이터, 공간 데이터, 모델 해석을 보여주기 좋습니다.  
다만 데이터 분석가 포트폴리오에서는 너무 모델 중심으로 설명하지 말고, 정책/시장 해석 관점으로 정리하는 것이 좋습니다.
