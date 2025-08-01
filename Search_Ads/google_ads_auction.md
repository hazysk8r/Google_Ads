# 🏆 Google Ads Auction
Google Ads Auction에서 Ad Rank에 영향을 주는 6가지 핵심 요소와 경매 시점 광고 품질 평가 기준에 대한 설명

## 🎯 Ad Rank와 광고 위치 결정 원리

### 📍 기본 개념
- **광고 위치(Ad Position)**: 광고가 나타나는 순서
- **Google의 목표**: 더 유용한 광고를 더 높은 위치에 표시
- **Ad Rank 역할**: 광고 노출 자격과 순서 결정
- **과금 방식**: 실제로 광고가 클릭을 받았을 때만 비용 지불

### 🏆 순위 결정 방식
일반적으로 **가장 높은 Ad Rank를 가진 광고가 최상위 위치**에, **두 번째로 높은 Ad Rank를 가진 광고가 두 번째 위치**에 표시됨 (이는 광고들이 relevant thresholds를 통과했다는 가정 하에)

## 🔍 Ad Rank의 6가지 핵심 요소

### 1️⃣ 💰 Bid 

#### 개념
입찰가를 설정할 때, 광고주는 Google Ads에 광고 클릭에 대해 지불할 **최대 금액**을 알려주게 됨

#### 특징
- **실제 지불 비용**: 종종 설정한 입찰가보다 **적게 지불**
- **유연성**: 언제든지 입찰가 변경 가능
- **최대 한도**: 설정된 금액을 초과하여 청구되지 않음

#### 부가적 요소
```
✅ 경쟁력 있는 입찰가 설정
✅ 성과 데이터 기반 조정
✅ 자동 입찰 전략 고려
✅ 정기적인 입찰가 검토
```

### 2️⃣ 🎯 Ad Rank Threshold 

#### 개념
고품질 광고를 확보하기 위해, 광고는 **특정 광고 위치에 표시되기 위한 최소 품질 thresholds**를 충족해야 합니다.

#### 목적
- **품질 기준 유지**: 낮은 품질의 광고 필터링
- **사용자 경험 보호**: 관련성 없는 광고 차단
- **위치별 차등 적용**: 상위 위치일수록 높은 threshold

#### 영향
```
높은 Ad Rank → threshold 통과 → 광고 노출
낮은 Ad Rank → threshold 미달 → 광고 미노출
```

### 3️⃣ 🌐 Context of a Person's Search 

#### 개념
광고 경매에서는 **Context가 중요**. Ad Rank는 다양한 검색 context 요소들을 기반으로 계산됨

#### 고려 요소들

##### **🔍 검색어 관련**
- **검색 용어**: 사용자가 입력한 구체적인 키워드
- **검색어의 성격**: 정보 검색, 구매 의도, 네비게이션 등

##### **👤 사용자 정보**
- **위치**: 검색 시점의 사용자 위치
- **기기 유형**: 모바일, 데스크톱, 태블릿
- **검색 시간**: 시간대, 요일, 계절

##### **🌍 환경적 요소**
- **기타 광고들**: 동시에 표시되는 다른 광고들
- **검색 결과**: 함께 노출되는 자연 검색 결과
- **사용자 신호**: 이전 행동 패턴 및 기타 속성

#### 맥락의 중요성
```
동일한 키워드라도
→ 검색 맥락에 따라 다른 Ad Rank
→ 다른 광고 순위 결과
```

### 4️⃣ 🔗 Asset Impact 

#### 개념
광고 제작 시 **링크, 이미지 등의 추가 정보**를 포함할 수 있으며, 이를 **Assets**이라고 함

#### 애셋 유형
- **링크**: 웹사이트의 특정 페이지 링크
- **이미지**: 제품이나 서비스 관련 시각 자료
- **전화번호**: 직접 통화 가능한 연락처
- **위치 정보**: 사업장 주소 및 방향
- **가격 정보**: 제품/서비스 가격 표시
- **앱 링크**: 모바일 앱 다운로드 링크

#### Google의 평가
Google Ads는 **asset과 기타 광고 형식이 광고 성과에 미치는 영향을 추정**

#### Asset의 효과
```
✅ 광고 노출 면적 증가
✅ 클릭률(CTR) 향상
✅ Ad Rank 점수 개선
✅ 사용자 경험 향상
```

### 5️⃣ ⭐ Auction-time Ad Quality 

#### 개념
Google Ads는 **광고 및 연결된 웹사이트가 보는 사람에게 얼마나 관련성 있고 유용한지**를 확인

#### Quality Score
- **Quality Score**: 광고의 quality에 대한 평가가 집약되어 있음. 보고용 지표, 실제 경매에서 사용되지 않음
- **Auction-time Ad Quality**: 실제 경매에서 실시간으로 평가되는 품질

#### 모니터링 및 개선
- Google Ads 계정에서 Quality Score 모니터링 가능
- 지속적인 개선 작업을 통해 품질 향상

### 6️⃣ 🏁 The Competitiveness of an Auction (경매 경쟁도)

#### 개념
경매의 경쟁 상황이 Ad Rank와 비용에 미치는 영향

#### 경쟁도에 따른 영향

##### **🤝 비슷한 Ad Rank인 경우**
```
두 광고의 Ad Rank가 유사
→ 각각 비슷한 opportunity to win을 가짐
→ 경쟁이 치열한 상황
```

##### **📈 Ad Rank 격차가 큰 경우**
```
Ad Rank 격차 확대
→ 상위 랭킹 광고 쟁취 가능성 증가
→ 하지만 더 높은 CPC 지불 가능성
```

#### 경쟁도의 영향
- **승리 확실성**: Ad Rank가 높을수록 광고 쟁취 확률 증가
- **비용 증가**: 확실한 승리를 위해 더 높은 CPC 지불
- **시장 상황**: 경쟁자 수와 품질에 따라 변동

## 🔍 Aution-time ad quality의 3가지 주요 평가 기준

Google이 Aution-time ad quality을 평가하는 데 **3가지 주요 요소**가 있음

### 1️⃣ 📈 Expected Click-through Rate 

#### 개념
광고가 표시될 때 **클릭될 빈도에 대한 예측**이며, 광고 위치를 고려하여 계산됩니다.

#### 사용자 피드백의 중요성
- **Google 전반**: 의사결정에 있어 사용자 피드백이 중요
- **클릭률의 의미**: 사용자들이 어떤 것에 반응하는지 보여줌
- **클릭으로 투표**: 사용자들이 클릭을 통해 각 검색어에 가장 적합한 광고를 결정

#### 집단 지성의 힘
```
수백만 명의 사용자
→ 클릭을 통한 투표
→ 각 검색어에 최적의 광고 결정
→ 지속적인 품질 개선
```

#### 개선 방법
- 매력적인 헤드라인 작성
- 명확한 CTA(Call-to-Action) 포함
- 키워드와 일치하는 광고 문구
- A/B 테스트를 통한 지속적 최적화

### 2️⃣ 🖥️ Ad Landing Page Experience 

#### 사용자의 기대
사용자는 **찾고 있는 것을 찾는 데 도움이 되는 광고 landing page**를 원합니다.

#### 관련성의 중요성
**높은 관련성의 landing page**는 더 높은 점수를 얻습니다.

#### 고품질 landing page의 조건

##### **📝 콘텐츠 품질**
- **적절하고 독창적인 콘텐츠**: 사용자의 과제 완수에 도움
- **관련성**: 광고 메시지와 일치하는 내용
- **유용성**: 실제로 도움이 되는 정보 제공

##### **🧭 사용자 경험**
- **쉬운 탐색**: 직관적이고 명확한 사이트 구조
- **빠른 로딩**: 페이지 로딩 속도 최적화
- **모바일 최적화**: 반응형 디자인

##### **🔒 투명성**
- **비즈니스 성격**: 명확한 사업 정보 제공
- **사이트 상호작용**: 사용자 컴퓨터와의 상호작용 방식 설명
- **개인정보 처리**: 개인정보 사용 의도와 방법 명시

#### 개선 전략
```
✅ 광고와 랜딩 페이지 메시지 일치
✅ 명확한 전환 경로 설계
✅ 페이지 로딩 속도 최적화
✅ 신뢰성 지표 추가 (인증서, 리뷰 등)
✅ 개인정보 보호정책 명시
```

### 3️⃣ 🎯 Ad Relevance 

#### 개념
광고 관련성은 **사용자가 검색하는 내용과 광고가 얼마나 잘 일치하는지**를 측정합니다.

#### 목적

##### **🎯 유용한 광고만 표시**
- 사용자에게 실제로 도움이 되는 광고만 노출
- 관련 없는 광고로 인한 사용자 경험 저하 방지

##### **🚫 무관한 광고 차단**
- 기업들이 자신의 제품이나 서비스와 **무관한 검색어에 단순히 돈을 지불하여 진입하는 것을 방지**
- 검색 의도와 광고의 일치성 확보

#### 관련성 평가 기준
- **키워드-광고 일치도**: 설정한 키워드와 광고 메시지의 연관성
- **검색 의도 부합**: 사용자의 실제 검색 의도와 광고의 적합성
- **메시지 일관성**: 광고 전체에서 일관된 메시지 전달

#### 개선 방법
```
✅ 키워드별 맞춤 광고 제작
✅ 검색 의도에 맞는 메시지 구성
✅ 광고 그룹 세밀한 분할
✅ 부정 키워드 적극 활용
✅ Dynamic Keyword Insertion 활용
```
