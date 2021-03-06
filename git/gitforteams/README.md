## Git for Teams  

##### 팀을 위해 git을 사용하자. 이건 단순히 git에 대한 이야기만은 아니다.  

```
"모든 팀과 모든 프로젝트에 딱 들어맞는 하나의 올바른 방법 같은 것은 없다. 의욕적이고 응집력 있는 팀을 만드는 방법은 팀의 모든 이들을 존중하고 가능한 한 그들의 선호에 따라 개발 과정을 최적화하는 것이다." - 팀을 위한 Git 중에서  
```
  
우리는 '팀을 위한 Git'이라는 책을 통해 Git을 활용해 팀을 효율적으로 관리하는 방법에 대해 살펴볼 것이다.  

이 문서는 필자의 주관이 다소 섞여있을 수 있기 때문에 어느정도 감안하고 보길 권장하는 바이다.  

#### 사고 전략  

우선 이 책이 독자에게 가장 말하고 싶은 핵심은 바로 '모두를 위한 올바른 방식'은 없다는 것이다. 일반적으로 팀을 위해 어떤 방식을 채용한다고 할 때 팀이 가장 효율적일 수 있는 방식을 선정한다.  

이런 상황에서 모든 팀원을 만족시키기란 쉽지 않다. 그렇기 때문에 팀장은 팀원들의 이야기를 듣고 어떻게 하면 팀원들이 문제 해결에 열중할 수 있을지에 대해 고민해야 한다.  

이러한 고민을 해결하기 위해서는 그 사람의 성향을 파악하는 것이 중요하다. 본 서에서는 팀원의 사고 전략을 다음 3가지로 구분한다.  

* 창조적 사고 전략  
* 이해하는 사고 전략  
* 결정하는 사고 전략  

이 3가지 유형의 사고 전략은 각기 일장일단을 지니고 있지만, 그 누구도 필요하지 않을 수 없다. 따라서 각자에게 맞는 대응으로 그들을 대해야 한다.  

> 자세한 설명은 책을 통해 확인하길 바라며 다음으로 넘어가도록 하자.  
  
#### 팀 회의  

본 서와 '게임스토핑 - 제임스 매카누포'에서 이야기하는 시작 - 진행 - 끝 시퀸스에 대해 살펴보자.  

회의를 준비할 때는 다음과 같은 패턴을 기억해야 한다.  

```
시작, 진행, 결론.  
```
  
불필요한 회의를 줄이기 위해 이와 같은 시퀸스를 명확하게 해야 한다. 예를 들어 다음과 같다.  

```
의제: 아이디어 회의 / 총 시간: 45분  

* 문제의 핵심 파악하기(10분)  
* 해결책 브레인스토밍(25분)  
* 아이디어 구조화하기(10분)  
* 테스트할 최선의 아이디어 세 가지 꼽기(5분)  
```
  
또한, 각 구성원들은 회의 전에 미리 회의의 목표를 확인하는 것을 필수적으로 해야 한다. 이는 문제를 파악하기 위해 자유로운 토론 시간을 갖는 것만큼이나 기본적인 것이다.  

#### 스프린트  

프로젝트가 시작되면 정기적으로 회의를 하고 싶어진다. 분산된 팀의 경우에는 일의 진행 상황을 숨기기 쉽고, 변명도 많아진다.  

이를 관리하기 위해서 회의 시간을 낭비할 수도 없기 때문에 팀이 성공하려면 아주 구체적인 목적을 가지고 그것을 이루기 위해 최소한의 회의를 진행할 수밖에 없다.  

그렇기 때문에 짧은 스프린트로 일하는 것이 권장된다. 이는 성과 목표를 아주 짧은 기간동안 달성할 수 있도록 나누어 일을 하는 방식인데, 이렇게 일하면 누구도 문제를 숨기기 어렵다.  

물론, 이는 팀원을 압박하며 일하라는 이야기는 아니다. 이것의 가장 큰 목표는 작업을 일정하게 진행하기 위함이다. 스프린트에는 다음과 같은 회의 방식이 존재한다.  

* 스프린트 계획하기: 스프린트를 계획하기 위한 회의이다. 여기서는 정해진 기간동안 달성할 목표를 선정하고, 진행될 계획에 대해 이야기한다.   

* 일정회의(15분): 여기서 팀원들은 자신의 작업에 관한 '약속'을 결과물로 내야 한다. 예를 들어 "오늘 무슨 일을 하는가?"에 대해서만 대답할 것이 아니라 "다음 일정 회의까지 제출할 부분이 무엇인가?"에 대해서도 대답하는 것이 효율적이다. 더 구체적인 이야기는 후속 회의에서 다룰 수 있다.   

> 약속 단계에서 가장 중요한 점은 약속에 대한 결과물에 대해 부끄러워하거나 비난하지 말아야 한다.  
>
> 이를 스크럼 용어로 '스탠드 업' 회의라고 한다.  

* 프로젝트 딥다이브(45분): 앞선 일정회의보다 깊은 토론이 필요하다면, 후속 딥다이브 회의를 해야 한다. 이상적으로는 누구나 팀원들이 여유가 되는 시간에 후속 회의를 잡을 수 있도록 하자. 보통 정해진 기간동안 45분의 딥다이브 회의를 한 두 차례 할 수 있도록 시간을 비워둔다.  

> 딥다이브 회의는 관련 팀원은 필수적으로 참여하고, 관심있는 팀원은 누구나 참석할 수 있도록 해야 한다.  

* 스프린트 데모: 작업 현황을 공유하는 시간이다. 정해진 기간 동안 함께 모여 작업 현황을 서로에게 보여줄 기회를 가져야 한다. 각자 정해진 순번(랜덤)에 따라 시연하면 최종 작업 결과물을 만드는 것과 같은 분위기를 만들어, 작업을 작고 처리 가능한 분량으로 나누는 역할을 한다. 이 회의를 통해 새로운 아이디어를 찾고 수정해야 할 버그를 확인할 수 있을 뿐 아니라, 이후 작업 스프린트 과정에 대한 개선책을 논의할 수도 있다.  

> 물론, 이 회의는 생략될 수 있다. 그 전제조건으로는 팀이 잘 화합하고 그 주 얼마나 팀 내 소통이 이루어졌는가에 따라 다르다. 그렇기 때문에 팀원들끼리 필요한 만큼 도움을 구하지 않는다거나 한다면, 스프린트 데모를 진행해 보자.  

* 스프린트 회고(60분): 매 스프린트가 끝날 때면 팀을 모아 작업 과정에 대해 논의해야 한다. 과정에서 잘 되고 있는 것과 개선할 것을 확인해야 한다. 가장 핵심적인 질문은 "무엇을 원하는가", "무엇이 필요한가", "무엇이 의문스러운가"이다.  

> 회고회의에서 가장 중요한 점은 프로젝트의 잘된 점과 개선할 점에 대한 토론이다. 이 토론의 결과로 향후 주의해야 할 사항들의 패턴을 확인하는 것도 중요하다. 즉, 호의에서 팀원들이 던졌던 질문을 바꿔 그 당시 얻었던 정보보다 나은 정보를 얻는 방법을 찾으려는 것을 말한다.
>
> 버전 관리라는 측면에서 프로젝트가 끝나면 프로젝트에서 가장 좋았던 것들을 찾고 어떻게 그것들을 만들 수 잇었는지를 문서로 만들면 좋다. 어쩌면 다시 사용해볼 만한 새로운 정보 구조화 방법이 있을 수도 있고, Git 저장소도 한 번 살펴보고, 특히 향후 프로젝트를 위한 문서에 예제로 사용할 법한 좋은 커밋 메시지도 찾아보도록 하자.  

이밖에도 필요하다면 다양한 스프린트 방법론을 추가할 수 있다. 또한, 팀 내에서 비즈니스적으로 사람을 대해 팀원을 하나의 '자원'으로 인식하는 경향을 줄이기위해 팀원간의 공감대를 구축하는 것이 중요하게 여겨진다. 이에 대해서는 추가적인 언급을 하지 않고 넘어가도록 하겠다.  

#### 팀 작업 관련 Git 용어  

개별 개발자들은 저장소 로컬 사본을 가지고 있다. 핵심적으로 이 사본은 프로젝트의 수정 히스토리의 독립 사본이라 할 수 있다. 이 수정사항을 공유하기 위해 개발자들은 저장소 사본을 GitHub와 같은 중앙화된 코드 호스팀 시스템에 게재한다.  

앞서 언급한 저장소 로컬 사본을 만드는 과정을 Git 용어로 Create Clone 또는 Forking이라고 부른다. 저장소 클론을 생성할 때, 소프트웨어 개발자들은 해당 프로젝트 사본을 비공개 또는 공개로 설정할 수 있다.  

> 비공개로 설정하면 다른 사람들이 해당 사본을 볼 수 없게 하여, 주 프로젝트에 공식적으로 적용된 수정 히스토리만 볼 수 있게 하는 것이고, 공개로 설정하면 누구나 해당 사본에 접근하여 직접 수정할 수 있도록 하는 것이다.  

오직 프로젝트 거버넌스를 통해서만 프로젝트의 가장 중요한 저장소 버전이 결정된다. 왜냐하면, 모든 저장소는 수정할 수 있고, 그 수정사항을 공유할 수 있기 때문이다.  

> 일반적으로 소프트웨어 제품의 공식 버전을 현재 저장소의 업스트림(upstream)이라 부른다.  

또한, 하나의 저장소 안에 프로젝트의 여러 버전을 저장할 수 있다. 이런 저장소 내 수정사항은 Branch를 통해 기록할 수 있다. 현재 Branch를 다른 Branch로 교체하려면, 교체하고 싶은 Branch를 Check out하면 된다.  

Git에서 Branch를 교체하려면, 먼저 Commit하지 않은 수정사항을 Commit, Stash, 또는 Discard 처리해야 한다.  

수정사항을 적용하는 과정에서 사용되는 명령어들은 다음과 같다.  

* Pull: 원격 저장소에서 수정사항을 가져와 자동으로 로컬 저장소에 적용한다. Pull은 중앙 저장소의 새로운 수정사항을 가져오는 fetch 기능을 수행하고 그다음 가져온 수정사항을 track(추적)ehls 로컬 Branch 사본에 병합하는 merge 기능을 수행한다.   

> 언제든 내 저장소의 로콜 Branch에서 작업할 수 있다. 작업한 결과를 다른 개발자들과 공유하고 싶다면 내 작업을 저장소에 커밋하고 push 기능을 이용해 나의 branch를 원격 저장소에 올린다.  


