<hr style="height:3px; background-color:#007bff; border:none;">

# Key Projects for Samsung C&T
This document provides an overview and description of the key projects conducted for Samsung C&T. Due to the **Non-Disclosure Agreement (NDA)**, the actual code used in these projects cannot be shared. Instead, **Sample Code** based on similar research papers or concepts is provided to illustrate the approach and methodology used in each project.

---

## 1. Commodity Price Forecasting (Steel, Copper, Aluminum) and Semiconductor/Non-semiconductor Equipment Price Forecasting

### Project Description
- **Objective**: Forecast the prices of key commodities like steel, copper, and aluminum, as well as semiconductor and non-semiconductor equipment, to support effective purchasing and investment strategies.
- **Scope**: Key raw materials in the industrial materials market and semiconductor-related equipment.
- **Role**: Derived business insights related to industrial materials across Samsung C&T's **Singapore office and Southeast Asia regions, including Australia**, and provided results to the headquarters’ strategic department.

### Technologies Used
- **Machine Learning Models**: Linear Regression, Random Forest, LSTM, Transformer-based models, and others.
- **Time Series Analysis**: Time series forecasting and trend analysis.
- **Tools**: Python, Pandas, scikit-learn, Statsmodels, PyTorch
  
- **Reference1(LSTM)**: https://github.com/JacobShin0601/yunchae-samsung/tree/main/TimeSeriesForecast-LSTM
- **Reference2(Transformer)**: https://github.com/JacobShin0601/yunchae-samsung/tree/main/TimeSeriesForecast-Transformer

### Outcomes
- Achieved high predictive accuracy for commodity price changes, providing valuable insights to support purchasing and investment strategies.
- Delivered results to Samsung C&T's strategic department, assisting in strategic decision-making within the industrial materials market.

---

## 2. In-House Consulting (for Samsung Electronics, Samsung Electro-Mechanics, Samsung Display in Vietnam)

### Project Description
- **Objective**: Supported **Digital Transformation (DX)** in the Vietnam factories of Samsung affiliates (Samsung Electronics, Samsung Electro-Mechanics, Samsung Display) and forecasted key data necessary for business decision-making to enhance operational efficiency.
- **Scope**: Data on power demand and energy management, factory operations, and time-series data for identifying arbitrage opportunities between commodities.
- **Role**: Developed power demand forecasting and anomaly detection models to promote efficient energy usage and applied **Dynamic Time Warping (DTW)** to identify de-synchronization points essential for arbitrage trading between commodities.

### Technologies Used
- **Forecasting Models**: Time series forecasting models (SARIMAX, XGBoost).
- **Anomaly Detection**: Anomaly detection algorithms (Auto Encoder-based detection).
- **Dynamic Time Warping (DTW)**: Used for identifying de-synchronization points for arbitrage trading opportunities between commodities.
- **Tools**: Python, scikit-learn, PyTorch
  
- **Reference1(XGBoost)**: https://github.com/JacobShin0601/yunchae-samsung/tree/main/TimeSeriesForecastingWithXGBoost
- **Reference2(AutoEncoder)**: https://github.com/JacobShin0601/yunchae-samsung/blob/main/AutoEncoder_on_sagemaker/1.training_on_local.ipynb
0 **Reference3(AutoEncoder Paper)**: https://openreview.net/attachment?id=HkgeGeBYDB&name=original_pdf
- **Reference4(WideDeep Model)**: https://github.com/JacobShin0601/yunchae-samsung/tree/main/WideDeepModel-torch
- **Reference5(WideDeep Model Paper)**: https://arxiv.org/abs/1606.07792 

### Outcomes
- Delivered customized power demand forecasting and anomaly detection models to key factories of Samsung Electronics, Samsung Electro-Mechanics, and Samsung Display, enhancing energy savings and operational efficiency related to **DX (digital transformation)**.
- Supported DX projects and business decision-making in strategic hubs such as the Vietnam factories, maximizing operational efficiency and managing operational risks effectively.
- Identified de-synchronization points through arbitrage analysis between commodities, aiding in the identification of market opportunities and the development of profitable trading strategies.

---

These projects contributed to strategic decision-making for Samsung C&T and provided additional data insights and operational efficiencies through collaboration with Samsung affiliates. The Sample Code on GitHub is based on similar concepts and methodologies used in the actual projects.

  


<hr style="height:3px; background-color:#007bff; border:none;">

# Key Projects for Samsung C&T
본 문서에 포함된 프로젝트들은 삼성물산에서 수행한 주요 프로젝트의 개요와 설명을 담고 있습니다. **Non-Disclosure Agreement (NDA)**'로 인해 실제 프로젝트에서 사용한 코드는 공개할 수 없으며, 동일한 논문이나 개념을 기반으로 한 **Sample Code**를 예시로 제공합니다. 이를 통해 프로젝트의 개념과 접근 방식을 이해하실 수 있습니다.

---

## 1. 원자재 가격 예측 (철강, 구리, 알루미늄) 및 반도체/비반도체 설비 가격 예측

### 프로젝트 설명
- **목표**: 철강, 구리, 알루미늄과 같은 주요 원자재와 반도체/비반도체 설비의 가격 예측을 통해 효과적인 구매 및 투자 전략을 수립.
- **분석 대상**: 산업소재 시장의 핵심 원자재와 반도체 관련 설비.
- **역할**: 삼성물산의 **싱가포르 법인과 호주를 포함한 동서남아 지역 전역**에서 산업소재 관련 비즈니스 인사이트를 도출하여 본사 전략 부서에 전달.

### 사용 기술
- **Machine Learning Models**: Linear Regression, Random Forest, LSTM, Transformer 기반 모델 등
- **Time Series Analysis**: 시계열 예측 및 트렌드 분석
- **Tools**: Python, Pandas, scikit-learn, Statsmodels, PyTorch
  
- **Reference1(LSTM)**: https://github.com/JacobShin0601/yunchae-samsung/tree/main/TimeSeriesForecast-LSTM
- **Reference2(Transformer)**: https://github.com/JacobShin0601/yunchae-samsung/tree/main/TimeSeriesForecast-Transformer

### 성과
- 주요 원자재 가격 변화에 대한 높은 예측 정확도를 달성하여, 관련 부서의 구매 및 투자 전략에 중요한 인사이트 제공.
- 삼성물산 전략 부서에 결과를 전달하여, 산업소재 시장에 대한 전략적 의사결정 지원.

---

## 2. 인하우스 컨설팅 (Samsung Electronics, Samsung Electro-Mechanics, Samsung Display in Vietnam 등)

### 프로젝트 설명
- **목표**: 삼성 계열사(삼성전자, 삼성전기, 삼성디스플레이 등)의 베트남 공장에서 **Digital Transformation (DX)**'을 지원하고, 사업 의사결정에 필요한 주요 데이터를 예측하여 경영 효율성을 높임.
- **분석 대상**: 전력 수요 및 에너지 관리 데이터, 공장 운영 데이터, 원자재 간 아비트라지 기회를 찾기 위한 시계열 데이터 등.
- **역할**: 전력 수요 예측 및 이상 탐지 모델 개발을 통해 효율적인 에너지 사용을 지원하고, 원자재 간 아비트라지 매매에 필요한 **비동기화(de-synchronization) 시점을 찾기 위해 Dynamic Time Warping (DTW)**을 활용.

### 사용 기술
- **Forecasting Models**: 시계열 예측 모델 (SARIMAX, XGBoost)
- **Anomaly Detection**: 이상 탐지 알고리즘 (Auto Encoder 기반 탐지)
- **Dynamic Time Warping (DTW)**: 원자재 간 아비트라지 매매 기회를 위한 비동기화 시점 탐색
- **Recomender System**: Samsung.com's mobile phone & accessory recommendation system
- **Tools**: Python, scikit-learn, PyTorch
  
- **Reference1(XGBoost)**: https://github.com/JacobShin0601/yunchae-samsung/tree/main/TimeSeriesForecastingWithXGBoost
- **Reference2(AutoEncoder)**: https://github.com/JacobShin0601/yunchae-samsung/blob/main/AutoEncoder_on_sagemaker/1.training_on_local.ipynb
0 **Reference3(AutoEncoder Paper)**: https://openreview.net/attachment?id=HkgeGeBYDB&name=original_pdf
- **Reference4(WideDeep Model)**: https://github.com/JacobShin0601/yunchae-samsung/tree/main/WideDeepModel-torch
- **Reference5(WideDeep Model Paper)**: https://arxiv.org/abs/1606.07792 

### 성과
- 삼성전자, 삼성전기, 삼성디스플레이의 주요 공장에서 맞춤형 전력 수요 예측과 이상 탐지 모델을 제공하여, **DX (digital transformation)**'과 관련된 에너지 절감 및 운영 효율성 향상.
- 전략적 거점인 베트남 공장에서의 DX 프로젝트 및 비즈니스 의사결정 지원을 통해 공장 운영의 효율성을 극대화하고 운영 리스크를 효과적으로 관리.
- 원자재 간 아비트라지 매매의 시점을 찾기 위한 비동기화 분석을 통해, 시장 기회를 파악하고 수익성 있는 거래 전략 수립 지원.

---

이 프로젝트들은 삼성물산의 전략적 의사결정에 기여하였으며, 삼성 계열사와의 협력을 통해 추가적인 데이터 인사이트와 운영 효율을 도출했습니다. GitHub의 Sample Code는 실제 프로젝트에서 사용한 방식과 유사한 개념을 기반으로 작성되어 있습니다.
