일곱번째 WIL 22.08.07
==============
## 회고 - 클론코딩 - Spring (08.01~04)
이번 프로젝트는 잘 흘러갔던 것 같다. 각자 맡은 역할을 잘 진행한 덕분에 하루일찍 프로젝트를 완성할 수 있었다. 내가 맡은 장바구니에서 오류가 있어
수정을 하느라 조금 시간이 더 걸렸지만 예상한 시간보다 일찍 끝내고 버그를 찾는데 시간을 더 보낼 수 있었다. 발표까지 끝내고 최종 프로젝트를 들어
가기전 푹 쉴수 있었다.
#### 배웠고 느꼈던 점
이번 장바구니에서 상당한 시간이 걸린 이유는 순환참조로 인해 데이터를 가져오는데 어려움이 있었기 때문이다. 일단 순환참조를 방지하기 위해 순환참조를 
일으키는 해당 객체에 @JsonIgnore 어노테이션을 붙어서 오류를 잡았다. 하지만 이러한 방법보다는 위와 같은 상황이 발생하게된 원인은 Entity 자체를 
response로 리턴하는데 있다. 리턴을 할때 Entity를 보내지 않고 DTO객체를 만들어 필요한 데이터를 옮겨담아 리턴하면 순환 참조와 관련된 문제를
사전에 방지할 수 있다고 한다. DTO를 사용할 이유에 대해 하나더 알아가는 좋은 오류였다.
##### 오늘, 언젠가 해야할 것
클론코딩 장바구니 순환 오류 DTO로 해결하기

## 회고 - 최종 프로젝트 - Spring (08.05~07)
마지막 프로젝트가 시작되었다. 나는 서비스팀이 아닌 스프링 심화반으로 들어가 스프링에 대해 좀 더 폭 넓게 알기위해 지원을 했고 3명에서 한팀이 
되었다. 회의를 통해 데이터와 트래픽 처리에 대한 기술를 활용할 수 있는 구인 구직 사이트를 제작하기로 했다. 아직 구체적으로 어떤 기술을 사용해야
하는지 모르는 상황이였기 때문에 그에 대해서는 멘토링을 통해서 자문을 구하기로 하고 SA를 완성시켰다.
#### 배웠고 느꼈던 점
멘토링을 통해서 느낀점을 적어볼까 한다. 내가 생각하던 심화반은 어떤 방향으로 나아가는 것이 좋을지에 대한 spring 이정표를 생각하고 들어왔지만 
아니였다. 자신이 원하는 기술을 사용하고 배우고 프로젝트를 만든다. 그부분에서 기술적인 부분을 조언을 하되 온전히 선택은 자신이 하는 것이였다. 나만 이렇게
생각하는 것이 아니였고 우리 팀에서 한분은 그 부분에 대해서 고심하고 끝에 결국 심화반에서 하차하시고 서비스팀으로 가시게 되었다. 2명으로는 팀을
진행하기에는 무리가 있다고 판단, 다른 팀에 한명씩 추가하는 식으로 진행될 듯 하다. 다른 팀은 A반 분들로 구성된 팀이라서 이번에 처음 작업을 하게 
될텐데 걱정이 많다. 갑자기 합류하게된 나나 참여하게된 팀의 분들도 서로 어색해지는 것은 당연한 수순일 것 같다. 일단 어떻게 될지 결정이 되고나서
생각하는 것이 좋을 것 같다. 내가 굴러온 돌이라면 새로운 시작을 하면 될듯하고 아니라면 계속해서 나아갈 듯 하다.  
##### 오늘, 언젠가 해야할 것
심사숙고해서 결정하기