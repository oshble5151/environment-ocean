# MSMIP : mjo SSt 민감도 모델 상호비교 프로젝트

# 해양 커플링은 기후 모델에서 MJO 시뮬레이션을 개선하는 것으로 알려져 있다.

# 이것은 같은 모델에서 커플드 모델과 대기단독에서의 mjo 시뮤레이션 스킬을 비교한 선행연구에서 주목되어 왔다

# 이러한 비교는 SST로 인해 강제되는 결합동합과 월평균 단독 대기 시뮬레이션 사이에서 만들어 진다.

# 이 비교의 결과를 설명하는 것은   커플과 비커플 모델 사이의SSt 평균상태와  SST-low-frequency 변동성에서의 차이점, 그리고 비 커플드 모델은 커플드에 존재하는  sub-monthly SST variability를 포함하지 않기 때문이다.

# 이러한 복잡성을 처리하기 위해 2가지 접근방식이 사용되었다.
## 1) 결합 시뮬레이션의 월평균 SST로 강제된 결합되지 않은 시뮬레이션 => 결합 모델의 SSt 평균상태와  SST-low-frequency 변동성을 포함하지만 sub-monthly SST variability는 배제한다.

## 2) 결합 시뮬레이션의 데일리 평균 SST에 강제된 결합 되지 않은 시뮬레이션 => sub-monthly SST variability 포함하지만 ,  precipitation in high-frequency SST forced simulations은 가장 따뜻한 SST anomaly와 일치하는 경향이 있기 때문에 SST가 hallmark quadrature SST-precipitation relationship을 잘못 제거하는 원하지 않는 결과를 가진다


# DeMott et al은 4가지 다른 모델과 함께 첫번째 어프로치를 사용했고 커플 모델에서의 발전된 MJO 시뮬레이션은  meridional moisture advection mechanism을 경유한? 동쪽으로의 동진을 선호하는 결합대 비결합 모델의 적도 정점 평균 수분 패턴의 결과라는 것을 발견했다

# DeMott et al은 sub-monthly ocean-atmosphere feedbacks 이 평균 습기 의 변화와 개선된 mjo의 시뮬레이션의 변화에 대해 책임이 있다고 결론내렸다.

# 결합된 모델 sst 어노멀리 의 어떤 측면이 열대 평균 습기 패턴과 MJO진행에 있어서  가장 중요한가

#  MSMIP은 이 질문에 답하기 위해서와 평균 상태습기 와 mjo 시뮬레이션에 대한 sub-monthly SST variability의 영향이 모델독립적인지 일관성이 있는지를 확인하기 위해서  디자인 되었다 
