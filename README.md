# 프로젝트 설명
### 프로젝트 명
-   심부전 예측 데이터를 이용한 심장 질환 예측 및 머신 러닝 모델 개발
  
### 프로젝트 개요 및 진행 배경
-   심혈관 질환(CVD)은 전 세계적으로 사망 원인 1위를 차지하고 있으며, 매년 약 1,790만 명의 목숨을 앗아가고 있음
-   심혈관 질환이 있거나 심혈관 위험이 높은 사람은 조기 발견 및 관리가 필요함
-   심혈관 질환을 조기 발견하기 위해 심부전 데이터를 분석하고 예측하는 머신 러닝 모델을 개발하고자 진행

# 데이터셋
### 출처
- https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction?select=heart.csv

### 속성
- Age : 환자의 나이
- Sex : 환자의 성별 [M : 남자, F : 여자]
- ChestPainType : 흉통 유형 [TA : 전형적인 협심증, ATA : 비정형 협심증, NAP : 비협심증 통증, ASY : 무증상]
- RestingBP : 안정시 혈압 [mm Hg]
- Cholesterol : 혈청 콜레스테롤 [mm/dl]
- FastingBS : 공복 혈당 [1 : FastingBS > 120 mg/dl, 0 : 그렇지 않은 경우]
- RestingECG : 안정시 심전도 결과 [Normal : 정상, ST : ST-T파 이상 (T파 역전 및/또는 ST 상승 또는 저하 > 0.05mV) , LVH : Estes 기준에 따라 가능성이 있거나 확실한 좌심심 비대를 나타냄]
- MaxHR : 달성된 최대 심박수 [60~202 사이의 숫자 값]
- ExerciseAngina : 운동 유발 협심증 [Y : 예, N : 아니요]
- Oldpeak : oldpeak = ST [우울증에서 측정한 수치]
- ST_Slope : 운동이 가장 활발한 ST 구간의 기울기 [Up : 오르막, Flat : 평탄, Down : 내리막]
- HeartDisease : 출력 클래스 [1 : 심장병, 0 : 정상]
