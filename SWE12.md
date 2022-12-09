# 12. 품질
포인트1. 소프트웨어 품질은 무엇이며 품질을 결정하는 특성은 어떤 것이 있는가?

포인트2. 품질 보증 활동을 위한 조직과 계획은 어떻게 하는가?

포인트3. 품질을 측정하는 방법은 무엇인가?

포인트4. 소프트웨어 검증 기법은 무엇인가?

포인트5. 프로세스를 개선하는 방법은 무엇인가?

## 12-1 소개
- 테스트 : 품질 보장하는 일반적인 방법 
  - 테스트만으로 소프트웨어 결함을 줄이고, 방지하는 것이 제한적인 이유 
    - 제품주기에서 테스트가 너무 늦게 수행
    - 테스트는 좁은 차원만 다룸
    - 테스트는 코드 품질만 향상

- 리뷰 : 테스트를 보완, 개발 초기에 검토할 수 있어 오류가 조기에 발견됨

- 품질보증
  - 개발자와 협력하여 소프트웨어 개발의 적절한 표준과 절차를 정의
  - 검토 및 감사를 통해 업무를 모니터링하여 확인
  - 품질목표를 향한 진행상황에 대해 상급 관리자 및 기타 이해관계자에게 피드백을 제공

- 품질 관리
  - 품질 계획, 품질관리 ,품질보증, 검증 및 여러가지 품질 관련 프로세스
  - 품질 목표를 정하고, 목표달성을 위한 프로젝트 실행을 관리 및 통제하기 위한 모든 활동
    - 리뷰 : 품질 지표에 대한 자세한 내용을 다름
    - 프로세스 평가 및 개선 : 프로세스의 품질과 평균 성능 개선에 관한 것  

### 12-1-1 품질 개념
품질에 관한 관점
- 관점에 따라 다르게 정의& 품질에 대한 정의에 따라 품질 관리 활동이 달라짐

- 고객만족
  - 사용자 만족도는 제품의 전반적인 요소를 기반으로 하며 품질은 그 중 하나
  ![image](https://user-images.githubusercontent.com/64974683/206732480-3f17c57f-7952-4f6f-91f0-f907c4227c03.png)
- 요구 적합성
  - 모호 x
  - 지정된 요구사항과 디자인 준수하는 제품이 높은 품질의 제품
  - 일정 수준 이상의 고급이라는 의미가 높은 품질
-  제품 품질
  - 여러 속성의 집합 > 품질을 결정

### 12-1-2 소프트웨어 품질
1. 시스템, 구성요소, 프로세스가 지정된 요구사항을 충족시키는 정도
2. 시스템, 구성요소, 프로세스가 고객 또는 사용자 요구나 기대를 충족시키는 정도
![image](https://user-images.githubusercontent.com/64974683/206733108-3a3e4c91-2107-4172-898a-3597c50ea8ec.png)

## 12-1 품질모델
: 소프트웨어에 대한 작업 관점이 어디 있느냐에 따라 품질 속성의 관심 달라짐
![image](https://user-images.githubusercontent.com/64974683/206733245-5cdde4c3-2cce-4529-aedf-c281ab96dee6.png)

품질 속성은 3가지 차원 존재
- 품질 요소 - 사용자에 의한 외부 관점
- 품질 기준 - 개발자 측면의 내부 관점
- 메트릭 차원 - 품질을 제어
![image](https://user-images.githubusercontent.com/64974683/206733442-e3ec418f-2a2c-4ca3-b0ed-d874bd5377f8.png)

품질 모델
- ISO/IEC 9126
  - 소프트웨어가 가질 수 있는 여러 가지 품질 특성을 정의함
  - ISO에서는 여섯 가지의 품질 특성을 정의함
- ISO와 IEEE에서는 품질 속성의 계층을 다르게 정의함
![image](https://user-images.githubusercontent.com/64974683/206733590-1aefd992-5fb0-4355-a4e3-db1e761601a2.png)

품질속성
- 신뢰성 : 소프트웨어에 요구된 기능을 명시된 조건 하에 실행하여 정확하고, 일관성 있는 결과를 생성하는 능력
- 강인성 : 요구된 기능을 어렵거나 예외적인 환경에서 수행할 능력
- 효율성 : 최소의 시간과 자원을 사용하여 원하는 결과를 생성하는 능력
- 상호운용성 : 소프트웨어가 다른 소프트웨어와 정보를 교환하는 능력
- 유지보수성 : 소프트웨어가 수리 및 진화될 수 있는 성질
- 테스트 가능성 : 소프트웨어에 요구된, 적용될 수 있는 모든 형식의 평가
- 이식성 : 여러 운영환경 및 플랫폼에서 실행될 수 있도록 변경이 가능한 성질
- 재사용성: 확장이나 커스텀화 없이 유사한 또는 다른 배경에서 사용될 수 있는 성질
- 모듈성: 모듈 컴포넌트의 통합이나 조정을 쉽게 만드는 성질

- 소프트웨어 유형과 품질의 관계
![image](https://user-images.githubusercontent.com/64974683/206734263-13d13e25-c597-4797-9eb8-0244bdc5ca1d.png)

## 12-3 품질 관리
- 소프트웨어 제품이나 아이템이 정해진 요구에 적합하다는 것을 보장하는 데 필요한 계획적이고, 체계적인 활동
- 품질 관리 기능
  - 프로세스와 표준의 정의
  - 품질 보증
  - 프로세스 개선
 ![image](https://user-images.githubusercontent.com/64974683/206734683-b5803b43-c737-4195-9984-0e8bf1b8980d.png)
 
 ### 12-3-1 품질 보증 조직
 - 관리적 활동 : 개발조직의 표준화 방법론을 잘 따르도록 한 것
 - 기술적 활동: 방법론을 잘 정의하는 것 
![image](https://user-images.githubusercontent.com/64974683/206734926-2e0d8231-70ea-42a6-b5b3-1fb1df5999a9.png)

### 12-3-2 프로세스와 표준을 정의
- 소프트웨어 개발, 품질 보증 관리 프로세스 및 방법론 정의
- 개발주기동안 품질보증 작업을 수행할 표준, 절차, 가이드 라인의 정의
- 품질 측정과 평가를 위한 품질 메트릭, 지표 정의
![image](https://user-images.githubusercontent.com/64974683/206735117-fecb984c-c6e6-4297-a64f-94c907ed18ed.png)

### 12-3-3 품질 보증 활동
1. 품질 계획
- 프로젝트 초반에 이루어지는 활동
- 특정 프로젝트에 대한 품질 계획을 작성
2. 품질 제어
- 프로젝트 전반에 걸쳐 이뤄짐
- 품질 계획의 실행을 모니터링하고 현실적으로 수정이 필요하면 품질 계획 수정
3. 품질 보증 제어
- 계획이 정확하게 잘 실행되고 있는지 확인
- 개발자가 품질 보증활동을 수행하도록 도와주는 것
- 품질 관련 데이터를 모아 데이터베이스를 사용하여 관리
- 관리자에게 프로세스 개선을 위한 제안을 하고, 수용된 제안이 적절히 실현되고 프로세스에 녹아들었는지 확인

### 12-3-4 인스펙션
품질 보증을 위한 검토 작업
![image](https://user-images.githubusercontent.com/64974683/206735788-b0fde690-b670-4559-baea-f39f3e068e91.png)
- 품질 개선과 비용 절감을 위한 기법으로 가용
- 프로덕트를 공통되는 오류, 변칙, 표준이나 관례의 부적합리스트와 체크해보는 작업

인스펙션 과정
![image](https://user-images.githubusercontent.com/64974683/206735951-810115e5-5202-4ec8-b12c-6d09aa6f0f10.png)

## 12-4 품질 측정
- 소프트웨어 측정 : 소프트웨어 속성의 객관적이고, 정량적인 평가
- 소프트웨어 메트릭 : 표준화된 소프트웨어 측정 방법

### 12-4-1 품질 측정의 유용성
품질 측정과 메트릭
- 요구분석, 설계, 구현, 문서화가 포함된 소프트웨어의 정량적인 평가

### 12-4-2 품질 메트릭
![image](https://user-images.githubusercontent.com/64974683/206736517-f9e37df8-d014-4d10-94e2-e7924e1e4b9d.png)

## 12-5 프로세스 개선
엔지니어링 프로세스가 경험에 따라 어떤 차이가 있는지 연구하고 모델 제시

- cmmi : 프로세스 성숙도를 위한 프레임워크
- 용도 
  - 성숙도 평가 기준
  - 능력을 스스로 평가하고, 개선의 방향을 
-





  
