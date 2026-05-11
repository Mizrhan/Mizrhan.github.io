---
layout: default
title: Marketing KPI Performance Analysis
permalink: /projects/marketing-kpi/
---

<div class="project-header">
  <div class="eyebrow">SQL · KPI · Campaign Diagnosis</div>

  # Marketing KPI Performance Analysis

  SQL을 활용해 마케팅 KPI를 산출하고, 일별·카테고리별·캠페인별 성과를 진단한 프로젝트입니다.
</div>

## Summary

| 항목 | 내용 |
|---|---|
| 목적 | 마케팅 성과 흐름과 캠페인 효율 진단 |
| 도구 | SQL, DuckDB, Jupyter Notebook, matplotlib |
| 분석 축 | Daily Trend, Category-Level, Campaign-Level |
| 산출물 | KPI 테이블, 성과 진단, pause/scale 캠페인 제안 |
| 링크 | [GitHub Repository](https://github.com/Mizrhan/Marketing_KPI_Performance_Analysis) |

## Problem

마케팅 성과는 단순 매출만으로 판단하기 어렵습니다. 비용, 수익, ROMI, ROAS, 카테고리별 효율, 캠페인별 성과를 함께 봐야 합니다.  
이 프로젝트는 SQL로 KPI를 직접 산출하고, 어떤 캠페인을 중단하거나 확대해야 하는지 판단하는 것을 목표로 했습니다.

## My Role / Contribution

- DuckDB 기반 분석 환경 구성
- SQL로 daily/category/campaign KPI 산출
- 캠페인별 진단 테이블 생성
- 성과 변화 시각화
- pause/scale 캠페인 제안 정리

## Key Findings

- 일자별 수익과 비용은 비례 관계를 보여 기본적인 수익 구조는 안정적으로 나타났습니다.
- 순이익률 변동성이 커서 단순 흑자 여부보다 변동 원인 분석이 필요합니다.
- social 계열 마케팅에서 적자 신호가 확인되었습니다.
- influencer 계열은 높은 순이익률과 총소득 비율을 보였습니다.
- 일부 캠페인은 pause, 일부 캠페인은 scale 대상으로 분류했습니다.

## Recommendation

- 낮은 효율 캠페인은 중단 또는 예산 축소
- 높은 ROMI/ROAS 캠페인은 확대 검토
- 일별 변동성이 큰 구간은 추가 원인 분석
- 카테고리별 예산 배분 기준을 KPI 중심으로 재설계

## Portfolio Note

이 프로젝트는 데이터 분석가 지원에서 가장 앞에 배치하기 좋습니다.  
이유는 SQL, KPI, 성과 진단, 액션 제안이 모두 포함되어 있기 때문입니다.
