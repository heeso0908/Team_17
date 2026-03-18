# ☕ Starbucks Marketing Analytics Project

> 스타벅스 고객 데이터를 활용한 마케팅 데이터 분석 및 시각화 프로젝트

---

## 📌 프로젝트 개요

스타벅스는 고객에게 다양한 프로모션을 제공하며,  
고객의 반응과 실제 구매 데이터를 기반으로 마케팅 전략을 최적화할 수 있습니다.

본 프로젝트는 스타벅스 고객 데이터(`profile`, `portfolio`, `transcript`, `starbucks_menu_260112`)를 활용하여  
**프로모션 반응, 구매 전환, 고객 특성별 행동 차이**를 분석하고,  
이를 바탕으로 **마케팅 인사이트 도출 및 Tableau 대시보드 제작**을 목표로 합니다.

### 배경
마케팅에서는 단순히 프로모션을 많이 발송하는 것보다  
**어떤 고객에게 / 어떤 오퍼를 / 어떤 채널로 전달해야 실제 구매로 이어지는지**를 파악하는 것이 중요합니다.

이를 위해 고객 데이터, 프로모션 데이터, 행동 로그 데이터를 연결하여  
**캠페인 반응 구조와 구매 전환 흐름**을 분석합니다.

---

## 🎯 분석 목표

- 고객 데이터 기반 프로모션 반응 패턴 분석
- 오퍼 발송 → 열람 → 완료 → 구매로 이어지는 전환 흐름 파악
- 고객 특성 및 프로모션 유형별 반응 차이 분석
- Tableau를 활용한 마케팅 대시보드 제작
- 데이터 기반 마케팅 전략 인사이트 도출

---

## 📦 데이터셋

| 항목 | 내용 |
| --- | --- |
| 데이터 출처 | [Starbucks Customer Data (Kaggle)]() |
| 주요 테이블 | `profile.csv`, `portfolio.csv`, `transcript.csv` |
| 추가 데이터 | `starbucks_menu_260112.csv` |
| 주요 분석 대상 | 고객 정보, 프로모션 정보, 행동 로그, 거래 내역 |

### 데이터 설명
- `profile.csv` : 고객 인구통계 정보
- `portfolio.csv` : 프로모션 정보
- `transcript.csv` : 고객 행동 로그 및 거래 정보
- `starbucks_menu_260112.csv` : 스타벅스 메뉴 정보

---

## 👥 팀원 및 역할

| 이름 | 역할 |
| --- | --- |
| 김혜수 |  |
| 김희선 |  |
| 문다현 |  |
| 송원우 | 팀장 |
| 오해찬 |  |

---

## 🗂️ 프로젝트 구조

```bash
project-name/
├── README.md
├── pyproject.toml
├── uv.lock
├── .gitignore
├── Data/                 # 원본 데이터 저장
├── Notebooks/            # 개인별 작업 폴더
│   ├── 김혜수/
│   ├── 김희선/
│   ├── 문다현/
│   ├── 송원우/
│   └── 오해찬/
├── Final/                # 최종 산출물 저장
├── References/           # 참고 자료 정리
├── Reports/              # 개인 작업 로그 정리
└── Images/               # 공유 이미지 저장

---

## 🛠 기술 스택

| 구분 | 내용 |
| --- | --- |
| Language | Python |
| Library | `pandas`, `numpy`, `matplotlib`, `seaborn` |
| Visualization | Tableau |
| Version Control | Git, GitHub |
| Environment | uv |

---

## 🔗 참고 자료

- [Starbucks Customer Data - Kaggle](https://www.kaggle.com/datasets/ihormuliar/starbucks-customer-data?select=transcript.csv)
- [Lucidchart ER Diagram Tool](https://www.lucidchart.com/pages/examples/er-diagram-tool)
- [draw.io / diagrams.net](https://app.diagrams.net/)
- [ERD 다이어그램 그리는 방법 - 내일배움캠프 블로그](https://nbcamp.spartaclub.kr/blog/erd-%EA%B0%9C%EC%B2%B4-%EA%B4%80%EA%B3%84-%EC%9D%B4%ED%95%B4%EB%A5%BC-%EB%8F%95%EB%8A%94-%ED%8C%81-19137)