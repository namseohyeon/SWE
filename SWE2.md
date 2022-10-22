# 목차
1. [소프트웨어생명주기](#소프트웨어-생명주기)
2. [프로세스](#프로세스)
3. [프로세스 모델](#프로세스-모델)
4. [지원프로세스](#지원프로세스)
5. [방법론](#방법론)
<br>

### 프로세스
- 소프트웨어 대한 공학적 접근의 핵심
- 어떤일을 하기 위한 특별한 방법으로 단계나 작업으로 구성됨
- 정의된 작업들을 어떤 순서로 어떤 방법으로 하는가를 다르는 것이 방법론 
- 작업의 순서를 따라서 제시된 방법으로 수행하면 원하는 결과를 얻게 됨
- <b>프로세스 없는 개발</b>
    - code and fix
        - 설계 없음
            - 설계의 중요성을 꺠달지 못함
            - 사용자의 높은 요구 수준에 도달하기 어려움
            - 구조가 나빠짐/ 코딩 수정의 반복
        - 계획없음
            - 목표가 없어 성과를 알 수 없음.
            - 비용과 일정 조정이 힘듬
        - QA 인식 없음
            - 체계적인 테스트 작업이나 품질 보증 차원의 활동에 대한 필요성의 인식이 없음
    - 프로그래밍 > 만족할때까지 수정 > (반복) < 개선을 위한 아이디어 짜기

### 프로세스와 방법론의 비교
<table>
<tr><td></td><td>프로세스(틀): 프로젝트의 작업 공정을 구성하는 일반적인 접근 방법</td><td>방법론(구체적)</td></tr>
<tr><td>특징</td><td>
        - 단계적인 작업과 순서의 틀을 정의<br>
        - 무엇을 하는가에 중점<br>
        - 결과물이 표현에 대하여 언급 없음<br>
        - 패러다임에 독립적<br>
        - 각 단계가 다른 방법론으로 실현가능<br></td>
        <td>        
        - 프로세스의 구체적인 구현<br>
        - 어떻게 하는가에 중점<br>
        - 결과물을 어떻게 표현하는지 표시<br>
        - 패러다임에 종속적<br>
        - 각 단계의 절차, 기술, 가이드라인을 제시<br></td></td>
<tr><td>사례</td><td>
        - 폭포수 
        - 나선형
        - 프로토타이핑
        - unified 
        - 애자일<br></td>
    <td>
    - 구조적 분석, 설계 방법론<br>
    - 객체지향 방법론<br>
    - 컴포넌트<br>
    - 애자일 방법론<br>
    </td></tr>
</table>

### 소프트웨어 생명주기
- SDLC
- 소프트웨어 개발에 대한 기술적, 관리적, 이슈를 다루는 작업
    - 개발 모델별 컴포넌트 프로세스, 부프로세스 존재
    - 서로다른 목적
    - 서로 협력하여 전체 목적을 만족
    - 요구분석 > 설계 > 구현 > 테스팅 > 유지보수

### 프로세스
- 프로젝트는 단계로 이우러지며 각 단계는 프로젝트의 목표를 만족시킬 수 있는 잘 정의된 작업으로 정의되어야함
- 정형화되어 한 눈에 보여야함
    - 어떤 단계의 결과가 무엇이고, 누가 만든 것이라는 등의 개괄적인 정보에 머무르면 안됨
- 작업결과와 검증조건을 명확히 정의해야함
    - 요구 분석서, 설계 문서, 코드, 프로토 타입 등
- 작업 방법: 너무 많은 단계로 나누면 문서나 결과물이 너무 많아짐
- 진입조건(시작 전제 조건), 출구조건(종료조건)
- 프로세스 관리를 위한 정보 생성(프로세스를 컨트롤하기 위하여 적절한 조치를 할 때 사용)
- 소프트웨어 시스템을 구축하기 위해 수행되는 작업의 단계
- 동시에 수행되는 여러 단계 중 소프트웨어 개발에 대한 기술적, 관리적 이슈를 다루는 작업
- 프로세스와 프로세스 모델
- 소프트웨어 프로젝트
    - 수행할 작업을 조직화한 프로세스를 이용
    - 비용, 일정, 품질에 대한 목표를 성취하는 것
- 프로세스 명세
    - 프로젝트에서 수행해야 하는 작업과 아들의 수행 순서를 정의
    - 실행 프로세스는 실제 프로젝트의 순서와 다를 수 있음
    - 높은 품질, 낮은 비용, 일정 단축을 달성하는 수단
- 프로세스 모델
    - 일반적인 프로세스를 기술한 것
    - 소프트웨어 시스템을 주축하기 위해 수행되는 작업의 단계
    - 소프트웨어 개발에 대한 기술적, 관리적 이슈를 다루는 작업
    - 프로젝트를 위하여 알맞은 프로세스를 개발하기 위한 일반적인 가이드라인

#### 프로세스의 종류
- 프로젝트의 중심 프로세스 
    - 개발 프로세스
        - 프로젝트에서 수행하는 가장 중심
        - 수행해야할 개발작업과 품질 보증
    - 관리 프로세스
        - 작업을 계획하고 모니터링하는일
        - 비용, 품질, 기타목표를 맞추기 위한 계획, 제어작업
    - 형상 관리 프로세스
        - 변경을 관리하여 제품의 일관성을 유지
- 기타 프로세스
    - 프로세스 관리 프로세스

#### 좋은 프로세스의 특성
- 적합한가를 판단하는 기준
- 예측가능성
    - 완성하기 전 얼마나 정확하게 예측할 수 있는지
    - 비용을 예측
    - 품질 예측
    - 예측 가능한 프로세스를 사용해야함
- 테스팅과 유지보수 용이성
    - 유지보수 비용이 개발비용 초과
    - 전체비용을 줄이려면 개발의 목표가 유지보수 노력을 줄이는 것이 되어야함
    - 코딩은 전체노력의 1/3
    - 프로그래머가 사용하는 시간
    - 프로세스의 목적은 설계와 코딩에 드는 노력을 낮추는 것이 아니라 테스팅과 유지보수에 드는 노력을 낮추는 것
- 변경지원
    - 변경을 쉽게 다룰 수 있는 프로세스
    - 조직과 비즈니스도 변하면 소프트웨어도 변경 필요
    - 고객의 요구가 프로젝트 중간에 변경될 수 있음
    - 변경은 항상 일어나므로 변경을 쉽게 다룰 수 있는 프로세스 필요
- 결합제거
    - 단계별 오류 발생지점(분석 단계 20%, 설계 단계 30%, 코딩 단계 50%)
    - 요구에 오류가 있다면 설계와 코드에도 영향을 줌
    - 오류 탐색과 코드에도 영향
    - 오류탐색과 수정은 개발 전체 단계에 지속전인 프로세스가 되야함
    - 품질 보증 작업을 프로세스 전체와 각 단계별로 해야함

#### 프로세스 모델
- 일반적인 모델이 될만한 프로세스를 기술한 것
- 대표적인 프로세스 모델
    - 폭포수 모델(전통적)
    - 프로토타이핑 모델(사용자의 피드백을 중시)
    - 나선형모델(위험 관리를 중요시)
    - 점층적 개발 모델(단계적 개발 방법)
    - V모델(테스트와 검증을 강조)
    - 애잘일 프로세스(프로그래밍에 집중하여 반복 수행)

### 계획 > 요구분석 > 설계 > 구현 > 테스트 > 운영, 유지보수

##### 계획
- why 단계(Retrun On Investment) concept 정립
- 범위정하기
- 산정
- 리스크 분석
- 일정 계획
- 관리 전략 수립

##### 요구 분석
- 요구: 시스템이 가져야할 능력과 조건
- what 단계
- 응용분야(도메인)에 집중
- 가장 중요하고 어려운 단계(작은 차이가 큰 오류로 변함)
- 결과물: 요구분석서

##### 설계
- How의 단계
- 솔루션의 집중
- 아키텍처 설계
- UI 설계
- 상세 설계
- 결과물: 설계서(SD)

##### 구현
- Do it의 단계
- 코딩과 단위 테스트
- 설계 또는 통합 단계와 겹치기도 함
    - 전체 일정을 줄이기 위해
    - 협력 작입이 필요한 경우
- 특징
    - 압력 증가
    - 최고의 인력 투입
- 이슈
    - lat minute change
    - communication ovewhead
    - 하청관리

##### 통합과 테스트
- 병행(통합해 나가면서 테스트 시작)
- 모듈의 통합으로 시작
- 점차 완성된 모듈 추가
- 통합은 개발자가 주로 담당
- 테스트는 QA팀이 주로 담당
- 단계적인 테스트
    - 단위,통합, 시스템
- 목적 중심 테스트
    - 스트레스 테스트, 성능 테스트, 베타 테스트, Accepttance 테스트, Usabiliy 테스트

##### 설치와 유지보수
- 시스템의 타입에 따라 다른 설치 방법
- 이전 정책
- 시스템의 사용을 시작하게 하는 방법
- 설치는 개발 프로젝트의 일부, 유지보수는 별개
- 유지보수
    - 결함을 고침
    - 새 기능 추가
    - 성능 개선 및 추가

##### 폭포수 모델
- 1970년대 소개
- 항공방위 소프트웨어 개발 경험으로 습득
- 가장 오래, 널리 사용
- 각 단계가 다음 단계 시작 전에 끝나야함
    - 순서적(각 단계 사이에 중복이나 상호작용 없음)
    - 각 단계의 결과는 다음 단계가 시작되지 전에 점검
- 직능 중심의 프로젝트 조직
- 결과물 정의가 중요
- 크고 복잡한 오래 지속되는 프로젝트에 적합

##### V모델
- 검증을 강화하는 관점에서 폭포수 모델을 확장한 모델
    - 코딩 단계에서 위로 꺾여 올라가며 검증
![V모델](https://blog.kakaocdn.net/dn/qL8ru/btqDweVcx3i/9ZL98zvIktnHn9Ms3sRPXk/img.png)

##### 폭포수 모델 
- 장점
    - 프로세스 간단 > 초보자 사용 좋음
    - 중간 산출물이 명확, 관리하기 좋음
    - 코드 생성 전 충분한 연구와 분석 단계
- 단점
    - 소용없는 다종의 문서 생산 가능성 있음
    - 애매한 부분이 남아 있거나, 프로세스 진행과정에 변경될 수 있는데 이를 수용할 수 없음
    - 테스트 작업이 프로젝트 후반, 즉 시스템이 완성 후 시작
- 적용
    - 이미 잘 알고 있는 문제나 연구 중심 문제에 적합
    - 변화가 적은 프로젝트에 적합

##### 프로토타이핑 모델
- 요구 사항 피드백을 받기 위해 시스템을 실험적으로 만들어 사용자에게 보여주고 평가하는 방법
- 쓰고 버리는 일회용과 계속 발전시켜 나가는 진화형 
![프로토타이핑모델](data:image/jpeg;base64,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)
- 프로토 타입의 적용
    - 사용자의 요구를 더 정확히 추출
    - 알고리즘의 타당성, 운영체제와의 조화, 인터페이스의 시험 제작
- 프로토타이핑의 도구
    - 화면 생성기
    - 비주얼 프로그래밍, 4세대 언어
- 공동 참조의 모델
    - 사용자와 개발자의 의사소통을 도와주는 매개체
- 프로토 타입의 목적
    - 단순한 요구 추출- 만들고 버림
    - 제작 가능성 타진 - 개발 단계에서 유지보수가 이뤄짐
- 장점
    - 사용자의 의견 반영 잘됨
    - 사용자가 더 관심을 가지고 참여, 개발자는 요구를 더 정확하게 도출
- 단점 
    - 오해, 기대심리 유발
    - 관리가 어려움(중간 산출물 정의가 난해)
- 적용
    - 개발착수시점에 요구가 불투명할 때
    - 실험적으로 실현 가능성을 타진해보고 싶을때
    - 혁신적인 기숳을 사용해보고 싶을때

##### 나선형 모델
![나선형모델](https://m1.daumcdn.net/cfile215/image/192BD20F4C60FB2447C6BB)
- 소프트웨어 기능을 나누어 점진적으로 개발
    - 실패의 위험을 줄임
    - 테스트 용이
    - 피드백
- 여러번의 점층적인 릴리스
- Boehm이 제안
- 반복 순환 단계
    1. 목표, 방법, 제약 조건 결정
    2. 위험 요소 분석 및 해결
    3. 개발과 평가
    4. 다음 단계의 기획
- 장점: 
    - 대규모 시스템 개발에 적합 - 위험 리스크 낮아짐
    - 반복적인 개발 및 테스트 - 강인성 향상
    - 한 사이클에 추가못한 가능은 다음 단계에 추가가능
- 단점:
    - 관리가 복잡
    - 위험 분석을 잘못하여 지나친 경우 피해가 큼
    - 성공 사례 많지 않음
- 적용
    - 재정적 또는 기술적으로 위험 부담이 큰 경우
    - 요구사항이나 아키텍처 이해에 어려운 경우

##### 진화적 모델
- 개발 사이클이 짧은 환경
    - 빠른 시간 안에 시장에 출시해야 이윤에 직결
    - 개발 시간 줄이는 법 - 시스템 나누어 릴리즈
    - 시스템 핵심 부분에 대하여 기능이 명확하고 개발 효과도 좋은 부분을 우선적으로 개발
    - 요구분석, 설계, 구현, 테스트 싸이클을 반복, 반복적 모델이라고도 함
- 시스템을 발전시키는 법
    - 점증적 방법 - 요구명세의 기능별 서브 시스템으로 릴리스& 추가
    - 반복적인 방법 - 전체의 대상, 릴리즈할때 마다 기능의 완성도를 높임
    ![진화적모델](data:image/jpeg;base64,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)
- 장점
    - 몇가지 기능이 부족해도 초기에 사용 교육 가능
    - 사용자의 요구를 빠르게 반영
    - 시장을 빨리 형성
    - 가동 중인 시스템에서 일어나는 예상하지 못했던 문제를 신속하고 꾸준하게 고쳐나갈 수 있음
- 단점
    - 프로젝트 관리 복잡 > 큰 프로젝트에 부적합
    - 끝이 안보일 수 있어 실패의 위험이 커짐
    - 프로젝트의 진행이 위험 분석에 크게 의존

###### Unified 프로세스
- 여러개의 싸이클로 구성, 각 싸이클은 시스템을 출시함으로 종결
![unified프로세스](https://blog.kakaocdn.net/dn/bf0Tg6/btqDuryDPpa/dggrQIOMEvScUy96WSbVzk/img.jpg)
- 도입
    - 1,2 회 정도 반복으로 도입 단계를 진행
    - 간단한 유스케이스 모델과 소프트웨어 구조, 프로젝트 계획을 작성
- 구제화, 정련
    - 여러번의 반복 과정으로 이루어짐
    - 대부분의 유스케이스를 작성
    - 아키텍펴 설계
- 구축
    - 남아 있는 유스케이스에 대하여 구현하고 통합
    - 시스템을 목표 환경에 점증적으로 설치
- 전환, 전이
    - 시스템을 배치, 사용자를 교육
    - 베타 테스팅, 결함 수정, 기능 개선
- 장점
    - 방법론과 프로세스가 잘 문서화되어 있어 교육받기 좋음
    - 고객의 요구변경과 관련된 리스크를 적극적으로 해결
    - 통합을 위한 노력과 시간을 줄일 수 있음
    - 쉽고 빠르게 코드를 재사용
- 단점
    - 프로세스 복잡> 이해하기 어려움 > 정확하게 적용 어려움
    - 프로젝트 참여자들의 협동, 의사소통에 대한 가이드 없음
    - 조직화되지 않은 개발로 완전히 알려지지 않은 형태의 소프트웨어 개발로 이어질 수 있음

##### 애자일 프로세스
- 폭포수 프로세스의 단점 해결
- 절차와 도구보다는 개인과 소통을 중요시
- 실행되는 소프트웨어가 문서보다 가치있음
- 계약 절충보다는 고객 협력이 더 중요
- 계획을 따라 하는 것보다 변경에 잘 대응하는 것이 중요
- 전통적인 접근법이 팀의 형태에 따라 일이 조직되었으면, 애자일 접근법은 일을 중심으로 팀을 조직
- 사용사례 또는 사용자 스토리나 피처단위
- 테스트 중심 개발
- 2~6주간의 짧은 주기로 개발 반복
- 실행되는 소프트웨어를 개발하여 단계적으로 시스템 전체 완성
- 애자일 선언
    - 문서보다 커뮤니케이션을 통해 목표를 향함
    - 실행되는 소프트웨어를 통해 요구확인
    - 사용자의 요구는 바뀔 수 있음
    - 짧은 주기 동안 요구정의에서 구현, 테스트까지 이뤄지며 각 반복주기의 반성 의견을 다음 계획에 포함


##### 익스트림 프로그래밍
1. 사용자 스토리
 - 각 기능의 비즈니스 가치와 우선순위
2. 매일 빌드와 통합
3. 테스트 주도 개발
    - 코딩 전 요구상항 검증 테스트 시나리오 준비, 요구 기능을 명확히 하여 설계를 단순화
4. 페어 프로그래밍
    - 두명이 한대의 컴퓨터로 개발
    - 역할: 코딩, 검토
    - 수시로 역할 변경

##### 스크럼
- 개발 팀원 모두 소통, 협력하여 짧은 주기를 반복
- 작업, 역할, 결과물 백로그를 정하고 우선순위 부여
- 짧은 주기(스프린트)
- 애자일 방법론 중 하나
- 백로그(할일)

### 지원프로세스
- ISO/IEC 12207 에서의 프로세스 그룹(SDLC)에서 정의
- 지원프로세스 혹은 우산프로세스 필요
    - 프로젝트 관리 프로젝트, 형상 관리 프로세스, 품질 관리 프로세스

#### 관리 프로세스
- 대규모 프로젝트는 오랜기간 동안 많은 사람 참여
- 비용과 품질 목적을 달성하기 위해 프로젝트 관리하는 데 필요한 모든 작업
    - 계획: 목적에 맞는 개발 계획 수립, 일정, 비용
    - 모니터링과 제어: 계획대비 잘 진행되는지
    - 분석 : 계획과 실적의 차이에 대한 조치
- 프로젝트 모니터링과 제어는 개발 프로세스의 모든 단계를 포함하므로 가장 긴 기간동안 이뤄짐

#### 품질 프로세스
- 프로세스와 프로덕트에 대한 품질을 관리하고 향상시키는 것
- 인스펙션 프로세스
    - 전문인력이 담당
    - 개발결과에서 결함을 찾거나 방지하기 위한 노력
    - 정의된 프로세스에 따라 동료그룹이 작업 결과는 검사하는 것
- 프로세스 관리 프로세스 
    - 동적임

#### 형상관리프로세스
- 프로젝트는 변경이 지속적으로 일어남
- 개발 중에 발생하는 변경을 체계적으로 컨트롤 하는 것
- 개발작업과 독립적인 작업

### 방법론
- 소프트웨어 프로세스의 각 작업을 어떻게 수행하는냐를 정의
- 프로세스
    - 해야할 작업만 명시
    - 어떤 관계있는지 나타내지 않음
    - 입력 자료와 산출물을 정하고 있지만, 그 내용이 어떻게 표현되어야하는지 규정하지는 않음

#### 구조적 방법론
- 분리와 정복 원리 적용
- 자료 흐름도를 구조도로 변경하는 과정
    - 구조도: 모듈 사이의 관계를 나타내는 그래프
    - 모듈 사이의 관계는 제어흐름

#### 정보공학 방법론
- 정보시스템은 기업의 비즈니스와 밀접 관련
- 계획,분석,설계,구축 등의 기술집합이 기업의 부문과 연계 통합하는 방법 필요
- 1990년대 초 James Martin
- 기업전체의 조망과 데이터 통합의 어려움을 극복하기 위해 고안
- 정보공학 방법론의 특징
    - 기업중심: 기업의 전략경영을 지원하기 위해 초점
    - 전략적 시스템 계획 중심: 경영층의 요구와 견해 반영
    - 데이터 중심: 데이터 중심으로 설계 진행
    - 분할과 정복: 톱다운 방식으로 문제 > 비즈니스> 시스템
    - 공학적 접근: 분석, 설계 등 초기 단계에 철저히 작업
    - 사용자의 적극적인 참여: 초기부터 사용자를 참여시켜 불명확안 요구사항을 없앰
- 프로젝트 관점에서 요구하는 산출물
    - 설계: 스토리보드, 데이터 설계서, UI설계서, 
    - 개발 과정: 물리적 테이블과 프로그램 코드
- 절차와 방법
    1. 정보전략 계획 : 기업의 장기적 전략 계획 수립
    2. 비즈니스 영역 분석 : 비즈니스 영역별로 데이터와 프로세스 모델링, 연관성 분석
    3. 비즈니스 시스템 분석: 데이터와 프로세스 설계
    4. 시스템 구축: 데이터 상세 설계, 코딩

#### 객체지향 방법론(가장 많이 사용됨)
- 객체 사이의 인터랙션을 모델링하는 방법
    - 자료와 함수를 가까운 곳에 정의하여 객체로 묶고, 객체 사이에 메세지를 호풀하여 원하는 기능을 담당하게 함
- 객체지향 패러다임
    - 대규모 시스템을 클래스로 모듈화, 캡슐화 할 수 있는 좋은 방법
    - 주어진 작업을 수행하기 위해 협력하는 객체들의 모임이 시스템이라는 관점
    - OMT, Booch방법론, 유스케이스 접근법
    - 서로 다른 방법론을 이용하여 개발된 시스템을 통합하고 유지보수하는 것은 매우 불편, 비효율적
    - 통합된 방법이 요구되었거 이것이 UMP와 UP의 탄생동기

#### 세가지 방법론의 비교
<table>
<tr><td></td><td>구조적 방법론</td><td>정보공학 방법론</td><td>객체지향 방법론</td></tr>
<tr><td>특징</td><td>프로그램 로직 중심. 그림(DFD)을 그려 요구사항을 분석, 문서화하는 체계적인 방법</td><td>기업정보 중심. 전략 계획을 수립한 후 데이터 중심으로 CASE도구를 사용하여 공학적으로 접근</td><td>비지니스를 유스케이스로 분석하고 자료와 함수를 묶은 클래스를 파악하여 상호작용하는 객체들로 시스템을 구성</td></tr>
<tr><td>설계관심사</td><td>함수위주</td><td>자료위주</td><td>클래스위주</td></tr>
<tr><td>설계의 핵심</td><td>모듈</td><td>엔티티</td><td>객체</td></tr>
<tr><td>중심방법</td><td>프로그래밍 기법</td><td>기업의 전략 및 산출물 중심</td><td>설계의 표현</td></tr>
<tr><td>장점</td><td>검증된 방법/ 계획과 모니터링이 쉬움</td><td>데이터중심, 업무절차 및 환경변화에 유연</td><td>실세계와 밀접한 모델링 유지보수 쉬움. 설계 -> 코딩쉬움</td></tr>
<tr><td>단점</td><td>분석>설계 전환이 어려움</td><td>장기간필요. 특정사업영역으로 독립시스템 개발에 부적합</td><td>효용이 증명되지 못함 . 훈련된 개발자 부족</td></tr>
</table>
