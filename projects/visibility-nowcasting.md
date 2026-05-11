---
layout: default
title: Visibility Nowcasting
permalink: /projects/visibility-nowcasting/
---

<div class="project-header">
  <div class="eyebrow">Modeling · Weather/Air Quality · Imbalanced Data</div>

  # Visibility Nowcasting

  기상 데이터와 대기오염 데이터를 통합해 시정 예측 모델을 구축하고, 불균형 데이터 처리와 모델 비교를 수행한 프로젝트입니다.
</div>

## Summary

| 항목 | 내용 |
|---|---|
| 목적 | 시정 상태를 예측하고, 낮은 시정 구간의 예측 성능을 개선 |
| 데이터 | ASOS 기상 데이터, DataOn 대기오염 데이터 |
| 방법 | 데이터 통합, 전처리, 불균형 처리, LightGBM/XGBoost/딥러닝 모델 비교 |
| 평가 | CSI, F1, Accuracy |
| 링크 | [GitHub Repository](https://github.com/Mizrhan/Visibility_Nowcasting) |

## Why this project matters

시정 예측은 단순 회귀/분류 문제가 아니라, 낮은 시정과 같은 희소 이벤트를 얼마나 잘 탐지하는지가 중요합니다.  
따라서 이 프로젝트에서는 전체 정확도뿐 아니라 CSI와 같은 지표를 통해 중요한 구간의 예측 성능을 평가했습니다.

## My Role / Contribution

- 기상·대기오염 데이터 통합 구조 정리
- 전처리와 파생변수 설계
- 클래스 불균형 대응: SMOTENC, CTGAN
- LightGBM, XGBoost, ResNet-like, FT-Transformer, DeepGBM 등 모델 비교
- CSI/F1/Accuracy 기반 평가 및 모델 선택
- 지역/연도 기준 검증 구조 정리

## Process

1. ASOS와 DataOn 데이터를 병합
2. 결측, 자료형, 특수값 처리
3. 시간·월 주기형 변수 생성
4. 불균형 데이터 처리를 위한 SMOTENC/CTGAN 적용
5. GBDT와 딥러닝 모델 학습
6. 연도 기반 3-fold holdout으로 일반화 성능 검증
7. CSI, F1, Accuracy로 최종 성능 평가

## Key Takeaways

- 예측 문제에서는 “전체 정확도”보다 업무상 중요한 케이스를 잘 맞추는지가 더 중요합니다.
- 불균형 데이터에서는 단순 모델 변경보다 샘플링 전략과 평가 지표 설계가 중요합니다.
- 모델 성능 비교는 단일 점수보다 데이터 분할 기준, 지역 차이, 오차 패턴과 함께 해석해야 합니다.

## Portfolio Note

이 프로젝트는 데이터 분석가 포트폴리오에서는 “모델링을 할 수 있다”보다  
**복잡한 데이터를 구조화하고, 평가 기준을 설계하고, 성능의 의미를 해석할 수 있다**는 점을 강조하는 용도로 배치합니다.
