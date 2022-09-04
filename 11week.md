열한번째 WIL 22.09.04
==============
## 회고 - 최종 프로젝트 - Spring (08.29~04)
저번주에 리서치하던 Replication을 Spring에 적용을 했다. 먼저 실제 프로젝트에 적용을 하기전에 test 프로젝트를 만들어서 적용을 시켜보았다. 역시 이론과 실전은
다른법인지 적용하기 위해 다중 DB를 사용하는 방법을 알아야했고 그 과정에서 DataSourceConfig 를 통해 트랜잭션을 처리하는 직접 설정하는 방법도 배웠다.
#### 배웠고 느꼈던 점
확실한 것은 내가 사용한 코드에 대해서 20%도 이해하지 못했다는 것이다. 각각의 클래스와 어노테이션에 대해서 어떤 역할을 하는지는 이해를 했지만 하나로 모여서
동작을 했을때 어떤 순서로 어떤 메서드를 통해 트랜잭션이 이동하고 설정되는지 설명 할 수가 없다. 먼저 기본적인 jdbc에 대한 이해가 뒷받침이 되어야 한다고 느꼈다.
##### 오늘, 언젠가 해야할 것
jdbc, repository 동작 기술블로그 정리

## 참조 링크
* 내가 참여한 프로젝트
  [DG Times](https://github.com/DG-times)   
* 기술 블로그   
  [다중 데이터베이스(Multi DB)](https://www.notion.so/Spring-Multi-DB-87ffb1b3256d4c708641e9688c372076)     
  [Multi DB -DataSourceConfig](https://www.notion.so/Spring-Multi-DB-DataSourceConfig-71b4403ff70449f89d50be9424c82f4c)