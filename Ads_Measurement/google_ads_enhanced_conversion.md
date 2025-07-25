# 🔒 향상된 전환으로 측정 강화하기

## 개요
- 향상된 전환이 전환 측정의 정확도를 개선하여 Google AI 기반 솔루션을 강화하고 더 나은 성과를 제공하는 방법을 설명

## 🤔 향상된 전환이란?

### 💡 기본 개념

- **향상된 전환(Enhanced Conversions, ECs)**은 **자사 데이터를 Google의 데이터와 연결하여 전환과 ROI에 대한 더 정확히 파악할 수 있게** 해줌

- **고객이 웹사이트에서 전환을 완료할 때** 다음과 같은 자사 고객 데이터를 받을 수 있음:
    - 📧 **이메일 주소**
    - 👤 **이름**
    - 🏠 **집 주소**
    - 📞 **전화번호**

#### 🔄 위의 데이터 처리 과정
    1. **전환 추적을 위해 Google tag를 사용**
    2. **해시화 처리**
    3. **해시된 형태로 Google에 전송**
    4. **전환 측정 향상에 사용**

- **사용하는 향상된 전환 유형에 따라** 해시된 데이터가 측정 개선을 위해 다양한 방식으로 사용됨.

## 🌐 향상된 전환 for Web

### 🎯 기능 및 용도

- **향상된 전환 for web**은 **사용자가 전환할 때 웹사이트에서 해시된 자사 사용자 제공 데이터를 보내고 이를 Google 로그인 데이터와 매칭**할 수 있게 해줌.

- **사용 대상**: 구매나 가입과 같은 **온라인 웹사이트 전환**

### ⚙️ 작동 방식
<img width="1817" height="612" alt="ConversionLead" src="https://github.com/user-attachments/assets/ee073079-1ab5-4ae7-9cd5-97d0d9d703ce" />

1. **Google에 로그인한 사용자가 광고를 보거나 클릭하고 사이트에서 전환**
2. **전환 추적 태그를 통해 자사 고객 데이터 캡처**
3. **업계 표준 SHA-256 해싱 알고리즘** (안전한 단방향 알고리즘)을 사용하여 **데이터 해시화**
4. **해시된 데이터를 Google에 전송**
5. **Google의 로그인 사용자 데이터와 매칭**
6. **계정 내 전환으로 보고**

### 📊 지원 플랫폼 및 채널

- **현재 사용 가능한 플랫폼**:
    - Google Ads
    - Search Ads 360
    - Google Analytics

- **지원 채널**:
    - 🔍 **검색(Search)**
    - 📺 **YouTube**
    - ⚡ **Performance Max**

- **참고**: 웹용 EC는 **개인 식별 정보(PII)가 페이지에 있는 깊은 전환에서 가장 잘 작동함** (예: 구매 또는 확인 페이지)

## 📈 웹용 향상된 전환이 고객에게 도움이 되는 방법

### 🔍 증가된 전환 관찰 가능성

- **향상된 전환**은 **브라우저 및 규제 변화로 인해 손실된 전환을 복구**할 수 있게 해줌. **추가 자사 데이터를 기반으로 새로운 전환이 관찰**될 수 있음

### 🤖 개선된 모델링 및 입찰

- **향상된 전환**은 **어트리뷰션과 자동 입찰을 위한 AI 모델을 강화하는 추가적인 실제 데이터를 제공**하며, **사용자 기반 증분성 실험**도 제공하여 **전반적인 정확도를 향상**시킴

### 🛡️ 개인정보보호 준비

- **개인정보보호에 대한 사용자 기대 증가**로 인해 **개인정보보호 규정과 브라우저 제한이** 생기며 전환을 측정하는 방식이 변화하고 있음. **향상된 전환은 고객의 자사 데이터를 해시화하여 안전하게 개인정보를 보호**

- **개인정보보호 변화 예시**: Safari 사생활 보호 브라우징에서 링크 장식 사용 중단과 같은 개인정보보호 및 기술 변화가 업계 전반에 계속 출시되고 있으며, **향상된 전환은 크로스 기기 및 참여 뷰 전환 추적을 모두 보존**함

## 📋 향상된 전환 for lead

### 🎯 기능 및 용도

- **향상된 전환 for lead**은 **웹사이트 리드 양식의 해시된 first-party 사용자 제공 데이터를 사용하여 오프라인 판매와 거래를 측정**할 수 있게 해줌

- **사용 대상**: CRM의 자격을 갖춘 리드나 전환된 리드와 같은 **오프라인 전환**

### ⚙️ 작동 방식
<img width="1817" height="612" alt="ConversionLead" src="https://github.com/user-attachments/assets/30b62e9a-94d8-46f3-8827-67f2ae207623" />

1. **사용자가 광고를 클릭하고 웹사이트로 이동**
2. **사용자가 사이트를 탐색하고 제품이나 서비스에 대해 읽으며 자사 데이터 생성**
3. **이 정보가 비즈니스의 리드를 생성**
4. **웹사이트가 이메일 주소와 같은 해시된 리드 정보를 Google에 전송**
5. **CRM 데이터베이스에 이 정보 저장**
6. **리드가 전환될 때**(양식 제출 등) **해시된 리드 정보를 Google에 업로드**
7. **Google이 해시된 정보를 리드를 유도한 광고와 다시 매칭**

### 🔧 설정 방법

- **향상된 전환 for lead**은 다음을 통해 설정할 수 있음:
    - Google Tag Manager
    - Google 태그
    - Google Ads API

- **중요한 특징**: **향상된 전환 for lead은 Google 클릭 ID(GCLID)를 받기 위해 리드 양식이나 고객 관계 관리 시스템을 수정할 필요가 없음**

## 📊 향상된 전환 for lead이 고객에게 도움이 되는 방법

### 🔍 증가된 전환 관찰 가능성

- **향상된 전환**을 통해 **웹사이트 밖에서 일어나는 판매와 거래에 대해 캠페인을 보고하고 최적화**할 수 있음.

### 📈 개선된 보고 및 입찰

- **for lead 향상된 전환**은 **이메일 주소와 같은 사용자 제공 데이터를 사용하여 가져온 오프라인 전환 데이터를 보완**하고 **정확도와 입찰 성과를 개선하는 오프라인 conversion import의 업그레이드 버전**

### 🛡️ 개인정보보호 준비

- **Google 태그**가 전환 페이지에 정의된 고객 필드를 캡처하고 **자동으로 형식화하고 해시화**함
- **매칭된 데이터는 암호화**되고 **익명화된 데이터가 보고**됨
- **매칭되지 않은 해시된 데이터는 삭제**됨

---
