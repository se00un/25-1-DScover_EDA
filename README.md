# 25-1-DScover_EDA

# 비만도 예측 데이터셋

## 📌 소개
이 데이터셋은 멕시코, 페루, 콜롬비아의 14세에서 61세 사이의 사람들을 대상으로 수집된 비만도 예측 관련 정보입니다. 총 17개의 속성과 2,111개의 레코드로 구성되어 있습니다.  
본 데이터셋은 식습관, 신체 활동, 일반적인 신체 정보 등을 포함합니다.

## 📊 데이터셋 개요
- **총 데이터 개수**: 2,111개  
- **총 속성 개수**: 17개  

---

## 데이터 속성 설명
### 1. **기본 정보 속성**
| 컬럼명 | 설명 |
|--------|------|
| `id` | 각 데이터의 고유 식별자 |
| `Gender` | 성별 (남성 / 여성) |
| `Age` | 나이 (14~61세) |
| `Height` | 키 (미터 단위) |
| `Weight` | 몸무게 (킬로그램 단위) |

### 2. **식습관 관련 속성**
| 컬럼명 | 설명 |
|--------|------|
| `FAVC` | 고칼로리 음식 섭취 빈도 (Frequent consumption of high-caloric food) |
| `FCVC` | 채소 섭취 빈도 (Frequency of consumption of vegetables) |
| `NCP` | 하루 주식 섭취 횟수 (Number of main meals) |
| `CAEC` | 간식 섭취 빈도 (Consumption of food between meals) |
| `CH2O` | 하루 물 섭취량 (Consumption of water daily) |
| `CALC` | 음주 빈도 (Consumption of alcohol) |

### 3. **신체 활동 관련 속성**
| 컬럼명 | 설명 |
|--------|------|
| `SCC` | 칼로리 소비량 모니터링 여부 (Calories consumption monitoring) |
| `FAF` | 신체 활동 빈도 (Physical activity frequency) |
| `TUE` | 하루 기술 기기(스마트폰, 컴퓨터 등) 사용 시간 (Time using technology devices) |
| `MTRANS` | 주된 이동 수단 (Transportation used) |

### 4. **비만도 (NObeyesdad)**
`NObeyesdad` 컬럼은 BMI(체질량지수)를 기반으로 다음과 같이 분류됩니다.
Test 세트의 목적은 NObeyesdad를 예측하는 것입니다.

| 비만도 범주 | BMI 기준 |
|------------|---------|
| 저체중 (Underweight) | BMI < 18.5 |
| 정상 체중 (Normal) | 18.5 ≤ BMI < 24.9 |
| 과체중 (Overweight) | 25.0 ≤ BMI < 29.9 |
| 비만 I (Obesity I) | 30.0 ≤ BMI < 34.9 |
| 비만 II (Obesity II) | 35.0 ≤ BMI < 39.9 |
| 비만 III (Obesity III) | BMI ≥ 40 |

---
이 데이터셋을 활용하여 다양한 연구 및 분석을 수행해 보세요! 🚀
