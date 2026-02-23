# KBO-OBP-SLG-Analysis
KBO 공개데이터를 활용하여 23~25시즌의 OBP-SLG-Analysis
# KBO OBP vs SLG Analysis (2023~2025)
README.md  ← (요약 보고서)
├── data/
│     ├── kbo_2023.xlsx
│     ├── kbo_2024.xlsx
│     └── kbo_2025.xlsx

── notebook/
│     └── KBO-OBP-SLG-Alalysis.ipynb

## 1. 분석 목적
출루율(OBP)과 장타율(SLG) 중 어떤 지표가 승률에 더 큰 영향을 미치는지 분석하였다.

## 2. 데이터
- KBO 2023~2025 팀 기록
- 변수: OBP, SLG, OPS, 승률

## 3. 분석 방법
- 상관분석
- 다중회귀분석

## 4. 주요 결과

### 2023
- OBP 상관: 0.79
- SLG 상관: 0.53
- OBP 회귀계수: 4.1
- SLG 회귀계수: -0.8

→ 출루율 중심 리그 특성

### 2024
- OBP 상관: 0.87
- SLG 상관: 0.77
- OBP 회귀계수: 3.38
- SLG 회귀계수: 1.09

→ 장타 영향력 상승

### 2025
- OBP 상관: 0.91
- SLG 상관: 0.79
- OBP 회귀계수: 3.97
- SLG 회귀계수: 1.06

→ 출루 + 장타 모두 중요한 구조

## 5. 결론
최근 KBO는 출루 중심 리그에서 점차 장타 비중이 커지는 흐름을 보인다.
