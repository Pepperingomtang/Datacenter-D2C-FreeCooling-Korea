# 국내 기후 조건 기반 수냉식 데이터센터 Free Cooling 입지 적합성 평가
### Site Suitability Assessment for Free Cooling in Water-Cooled Data Centers in Korea

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Pepperingomtang/Datacenter-D2C-FreeCooling-Korea/blob/main/수냉식데이터센터_Free%20Cooling_냉방시스템%20모델.ipynb)

국내 5개 지역(춘천·구미·세종·울산·해남)의 시간별 기상 데이터를 바탕으로,
수냉식 데이터센터(40MW)에 Free Cooling 도입 시의 에너지·경제성·환경성(3E)을
정량 분석한 종합설계 프로젝트입니다.

## 핵심 인과 구조
기후 데이터 → 습구온도(T_wb) → 냉각탑 출수온도 → 칠러 COP → 운전모드 → 전력 소비 → 3E 지표

## 주요 결과
- 전 지역에서 Free Cooling 경제성 성립
- 춘천 최우수 (절감률 약 25.6%, 회수기간 약 2.9년)
- 위도가 아닌 습구온도가 입지 적합성을 결정 (구미 > 세종 역전 현상)
- 상세 수치: `3E_분석결과_40MW.xlsx` 참조

## 파일 구성
| 파일 | 설명 |
|---|---|
| `수냉식데이터센터_Free Cooling_냉방시스템 모델.ipynb` | 냉방 시스템 시뮬레이션 모델 (계산 엔진) |
| `3E_분석결과_40MW.xlsx` | 3E 분석 최종 결과 |
| `*_2025_기후데이터원본.csv` | 5개 지역 시간별 기상 데이터 |
| `서울지역_KT가산 데이터센터 비교_월간 소비 전력량 비교.xlsx` | 모델 검증용 비교 자료 |
| `Free Cooling 3E 종합분석_기본안내사항.docx` | 데이터 출처 및 분석 가정 설명 |

## 실행 방법
위 "Open in Colab" 버튼 클릭 → 런타임 실행

## 데이터 출처
기상 데이터: 기상청 기상자료개방포털 (https://data.kma.go.kr)
※ 공공누리 제1유형(출처표시)

## 저자
- 김민석, 김세광
- 아주대학교 건축공학과 | 지도교수: 안형욱

## 라이선스
이 저작물은 CC BY-NC 4.0 (저작자표시-비영리) 라이선스를 따릅니다.
