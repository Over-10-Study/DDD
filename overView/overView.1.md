### 도메인은 무엇인가요?
* 사용자 활동에 도움되는 소프트웨어를 만들기 위해서, 개발팀은 사용자의 활동과 관련된 지식체계에 집중해야한다. 이런 지식의 체계(영역)가 도메인이다.

### 모델은 무엇인가요?
* 도메인 지식의 폭은 광범위하고 위압적이다. 개발팀은 이런 부담을 해소하기 위해서 모델을 활용한다. 
* 모델은 지식을 선택적으로 단순화하고 의식적으로 구조화한 형태다. 우리는 적절한 모델을 토대로 정보를 이해하고 문제 자체에 집중할수 있다.
* 모델은 도메인 지식을 조직화하고 가장 중요한 요소를 구분하는 팀의 합의된 방식이다.

### 도메인 모델링은 무엇인가요?
* 모델링은 현실 세계에 실체를 사실적으로 만드는 것이 아니다. 현실 세계에 실재하는 사물(or 실체가 없는 사물)을 인위적으로 창조하는 행위다.
* (!)모델링은 필요한 결과를 내는 소프트웨어 매커니즘을 만드는 것이 아니라, 어떤 목적에 따라 제약에 구애받지 않고 현실을 표현하는 영화 제작같은 것이다.

### 도메인 주도 설계에서 모델을 사용하면 좋은점은?
* 모델을 기반으로 설계하고 구현하면, 유지보수와 계속되는 기능 개선에 도움이 된다.(바로 모델을 이해하면 코드를 해석할 수 있기 때문이다.)
* 모델을 기반으로 설계하고 구현하면, 개발팀은 의사소통을 하는데 있어서 별도의 번역절차가 필요 없다. 또한 의사소통을 통해 모델을 정제하며 개발할 수 있다.
* 모델의 용어, 개념을 분류, 분류한 지식을 연결할 때 도메인에 관한 공통된 사고방식이 녹아있다. 개발자와 도메인 전문가는 공유 언어를 바탕으로 갖가지 정보를 모델로 만들어낼 때 효과적으로 협업할 수 있다.

### 도메인 주도 설계의 본질은 무엇인가요?
* 우리가 만드는 소프트웨어는 사용자를 위해 도메인에 관련된 문제를 해결하는 능력에 있다. 우리가 만드는 기능은 전부 이런 기본적인 목적을 달성하기 위한 도구일뿐이다. 개발자는 업무 지식을 증진하기 위해 도메인 연구에 몰두해야한다. 도메인 학습을 뒷전으로 하고 정교한 기술을 바탕으로 도메인 문제를 해결하려고 한다면, 도메인을 학습하고 모델링하는 일은 다른 이들의 몫으로 남계되고 도메인과 무관한 소프트웨어를 만들어낸다.

### 그럼 이 책에서 얻을 수 있는 것은 무엇이죠?
* 개발자들이 통찰력을 추구하고 효과적인 모델을 만드는데 활용할 수 있는 체계적인 사고 방식과
* 불규칙하게 뻗어 나가는 소프트웨어 애플리케이션에 질서를 부여할 수 있는 설계기법을 연마할 수 있다.
* 결국 하나의 모델이 구현, 설계 의사소통의 기초가 돼야한다.

### 모델을 도출하는 방법은?
* 시스템에 관해 이야기를 주고 받을 때 모델을 사용하라. 
* 모델의 요소와 상호작용을 이용한다. 
* 그리고 표현 해야할 것을 더 쉽게 말하는 방법을 찾는다.
* 발견된 새로운 아이디어를 다이어그램과 코드에 적용하라.

### 효과적으로 모델링 할 때 이점은?
1. 모델과 구현을 연계하려고 한다.
2. 모델을 기반으로 하는 언어로 소통한다.(보편언어)
3. 풍부한 지식이 담긴 모델을 개발한다.(모델은 단순히 데이터 스키마가 아니라 행위를 지니고 규칙을 이행하며 다양한 지식이 포함되어야 한다.)
4. 모델이 불필요한 개념과 필요한 개념이 묶여있을 경우 본질과 무관한 개념은 모두 제거할 수 있게 본질적인 개념만을 식별할 수 있도록 노력한다.
5. 스케치, 브레인스토밍, 다이어그램 등을 활용해 다양한 시나리오를 검토하고 말로 표현해본다. 그러면 명확하고 쉬운지, 아니면 어색한지 빠르게 감지할 수 있다.
6. 모델은 결코 완벽해질 수 없으며, 다만 계속발전해나갈 뿐이다. 모델은 도메인을 이해하는데 실용적이고 유용해야하며, 모델은 쉽게 구현하고 이해하기에 충분할 만큼 엄밀해야한다.

### 보편 언어(Ubiquitous Language)는 무엇인가?
* 개발자간, 도메인 전문가 간의, 코드 자체 표현을 포함한 공유된 모든 도메인 모델에서 파생된 언어를 말한다.
* 도메인 모델 용어
* BoundedContext의 이름
* 대규모 구조의 용어
* 여러 패턴 이름

### 예시)
* "Routing Service에 출발지, 목적지, 도착 시각을 전달하면 화물이 멈춰야할 지점을 찾고, 음 그것을 데이터베이스에 삽입한다." (모호하고 기술적이다.)
* "출발지, 목적지, 등등 이것들 모두 Routing Service에 넣으면 필요한 것이 모두 담긴 Itinerary(여행일정) 돌려받는다." (아직, 설명이 장황하다.)
* "Routing Service는 Route Specification(출발지, 목적지, 도착시간 등)을 만족하는 Itinerary(여행일정)를 찾는다." (간결하고, 명확하다.)


### 보편 언어(Ubiquitous Language)가 아닌 것은?
* 개발자간, 도메인 전문가 간의, 코드 자체 표현을 포함한 서로 공유되기 힘든 언어를 말한다.
* 또한 수준 높은 도메인 전문가도 해당 모델을 이해하지 못하는 상황이 발생하면, 모델이 잘못 된 것이다.
* 설계의 기술적인 측면
* 기술적인 용어
* 기술적인 디자인 패턴
* 개발자가 이해하지 못하는 업무 용어 <- 모델에 속하는 후보
* 모든 이들이 사용하지만 설계에 나타나지 않은 업무 용어 <- 모델에 속하는 후보

### 문서의 용도는 무엇인가?
* 문서는 '코드'와 '말'을 보완하는 역할을 해야한다.
* 문서는 코드가 이미 잘하고 있는 것을 하려고 해서는 안 된다.
* 익스트림 프로그래밍은 여분의 설계 문서를 전혀 사용하지 않고 코드 스스로 별도의 설명이 필요 없는 상태를 유지해야한다.