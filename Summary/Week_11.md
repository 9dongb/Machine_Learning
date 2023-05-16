# 11주차
## 1. 선형 회귀 (Linear Regression)
- 대표적인 **회귀 알고리즘**
- 간단하고 성능이 뛰어남
- 특성이 하나인 경우, 어떤 **직선을 학습**하는 알고리즘
- 종속변수 y와 한 개 이상의 독립변수 x와의 선형 상관 관계를 모델링하는 회귀분석 기법

## 1-1. LinearRegression 클래스 (sklearn.linear_model 패키지)
- coef_ 속성 : 기울기 | 계수(Coefficient) | 가중치(Weight)
- intercept_ 속성 : y절편

### 모델 파라미터 (Model Parameter)
- 머신러닝 알고리즘이 찾은 값 : coef_, intercept_
- 머신러닝 알고리즘의 학습 과정은 **최적의 모델 파라미터**를 찾는 것
- 이를 **모델 기반 학습**
- 앞서 사용한 k-NN은 모델 파라미터가 없고, 학습 데이터셋을 저장하는 것이 학습의 전부
- 이를 **사례 기반 학습**
₀ ₁ ₂ ₃ ₄ ₅ ₆ ₇ ₈ ₉

⁰ ¹ ² ³ ⁴ ⁵ ⁶ ⁷ 
## 2. 회귀 분석 (Regression Analysis)
### 단순 선형 회귀 (Simple Linear Regression)
- 𝑦 = 𝛽₀ + 𝛽₁𝓍                            
- **종속변수 : 1, 독립변수 : 1**
### 다중 선형 회귀 (Multiple Linear Regression 또는 Multivariable Linear Regression)
- 𝑦 = 𝛽₀ + 𝛽₁𝑥₁ + 𝛽₂𝑥₂ + 𝛽₃𝑥₃ + ⋯ + 𝛽ₙ𝑥ₙ  
- **종속변수 : 1, 독립변수 : n**
### 다항 회귀 (Polynomial Regression)
- 𝑦ᵢ = 𝛽₀ + 𝛽₁𝑥 + 𝛽₂𝑥² + 𝛽₃𝑥³ + ⋯ + 𝛽ₙ𝑥ⁿ 
- **종속변수 : 1, 독립변수 : 1**
