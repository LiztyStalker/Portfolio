# 포트폴리오
1. 이력
2. 보유기술
3. 보유스킬
4. 진행한 프로젝트
	- [진행중] 야수디펜스 (Android, Unity) - [18.03 ~ 18.09 예정]
	- [출시, 팬게임] 케모노프렌즈 자파리동산 (Android, Unity) - [17.11 ~ 17.12]
	- [습작] 블러드루비 (Android, Unity) - [17.03 ~ 17.09]
5. 기타 프로젝트


## 1.이력 - 인디경력 (2년)

### [개인] 야수디펜스 - 디펜스 게임
#### [18.03 ~ 18.09 알파버전 예정]


### [개인] 케모노프렌즈 자파리동산 - 미니게임 모음
#### [17.11 ~ 17.12] 현재 1.6 버전 출시 - 4월


### [팀] 블러드루비 - 탑뷰 AOS 게임 
#### [17.03 ~ 17.09] - 습작


## 2. 보유기술
### 2.1 언어
__C# [숙련]__

-Unity C# 프로젝트 2년간의 다양한 게임 개발 경험 

(슈팅, 디펜스, 미니게임, 퍼즐, 3D 1인칭, 탑뷰 AOS 등)

-출시하여 운영을 해본 적이 있음 (케모노프렌즈_자파리동산 팬게임 – 1.6버전 출시)  

  
__Objective-C [기초]__

-Objective-C로 교육용 프로그램 개발 경험 있음. 차후 필요시 책으로 기술을 빠르게 습득 가능  

  
__C, C++, Java, PHP, JSP [기초]__

-기본적인 문법과 프로젝트를 진행한 경험이 있음. 차후 필요시 책으로 기술을 빠르게 습득 가능  




__DB__

__Mysql [기초]__

기본적인 Query문 사용 가능




__기타__

__Photoshop & Illustrator [숙련]__

-기본적인 편집과 드로잉 가능. 포토샵에 대한 웬만한 기능을 알고 있음

__PowerPoint, Excel [숙련]__

-빠르게 문서화 가능 및 Excel을 사용하여 Xml 출력. 함수 사용 가능

__Spine [기초]__

-애니메이션, Export 하여 유니티에 삽입 후 제어 가능



## 3. 보유스킬

__프로토타입 구현__

원하는 프로그램이 간략하게 돌아가는 프로토타입을 빠르게 제작하여 초반 재미성이 있는지 여부를 조사할 필요 있음. 


__알고리즘 및 자료구조 데이터관리__

리스트, 그래프, 트리, 해쉬, 정렬 등 기본적인 자료구조의 원리를 알고 있음

분할정복, 동적프로그래밍, 최소비용신장트리, 다익스트라, 프림알고리즘의 원리를 알고 있음

자료는 Xml로 저장하여 관리하며 엑셀에서 출력된 Xml을 곧바로 대입하여 데이터값을 확인할 수 있음


__AI를 구현하기 위한 행동트리와 FSM__

FSM으로 기초적인 AI의 행동을 개발할 수 있음 (야수디펜스) 차후에 확장성이 많이 필요하게 되면 행동트리로 개발하여 유연한 대처 용이 (블러드루비)


__Spine 플러그인 연동__

Spine을 연동가능. 애니메이션이 실행하는 데로 FSM, 행동트리에 대입하여 실행할 수 있음.


__UGUI 활용__

UGUI를 활용하여 원하는 UI를 만들어낼 수 있음. 필요한 이미지는 에셋을 사용하거나 직접 그리면서 대입


__프로그램 설계 - 기초__

기본적인 클래스 설계는 알고 있음. 필요시 디자인패턴을 습득하여 프로그램에 대입. 현재 프로토타입, 옵저버, 상태, 전략, 싱글톤, 반복자, 중재자, 데코레이터, 추상팩토리, 퍼사드 패턴을 알고 있음.


__GPGS 플러그인 연동 - 기초__

GPGS를 활용하여 사용자의 계정과 연동하여 데이터를 보존하거나 리더보드, 업적 등을 기록하고 출력하게 제작할 수 있음. 차후에 결제 및 이벤트를 익힐 예정


__Unity Editor 활용 - 기초__

Unity Editor를 활용하여 기본적인 값을 가져오고 데이터를 확인할 수 있음


__쉐이더 - 기초__

책을 구입하여 기본적인 쉐이더를 공부하고 있음. 


__깃허브 - 기초__

백업 및 협동하기 위하여 깃허브를 익히고 있음



## 4. 진행 프로젝트

### 프로젝트 명 : 야수 디펜스

개인 개발

버전 : 개발 중 - 알파버전 18.05.30

목표 : 18.09월 출시

플랫폼 : 안드로이드

장르 : Android 모바일 기반 디펜스 게임

개발툴 : Unity, C#, 비주얼스튜디오, Spine

링크 : 


__시스템 특징__

세갈래의 길

Top, Mid, Bot의 세 갈래의 길로 이동. 각 병사의 공격판정에 따라서 각 라인에 있는 적 공격. BoxCollider와 LayerMask를 사용하여 적을 판정.


버프관리

각각의 유닛에 버프를 삽입하여 가동. addBuff로 발동된 버프를 삽입 후 removeBuff 이벤트 등록. 차후에 버프 객체가 종료시 등록된 removeBuff 이벤트를 사용하여 List에서 제거.


스킬관리

Xml로 기본값 제어. 데이터를 삽입 후 불규칙적인 데이터는 Prefebs으로 제작 후 Skill 클래스에서 킷값을 찾아 등록. 추상클래스를 활용하여 SkillAction() 메소드 하나로 스킬 발동 처리. 


AI 동작 및 Spine 연동

FSM과 상태패턴으로 구현. 대기, 이동, 공격, 스킬, 사망 순으로 행동이 제어되며 현재 상태에 맞게 상태를 변경하고 Spine 애니메이션 실행.


이펙트 및 사운드

EffectManager와 SoundManager를 자체 제작하여 효과 출력. ParticleSystem과 AudioSource를 활용


GPGS 및 파이어베이스 연동 예정

GPGS와 파이어베이스를 연동하여 데이터보존 및 리더보드, 결제 제작, 상대방 데이터를 기반으로 전투장 개발 예정



### 프로젝트 명 : 케모노프렌즈 자파리동산

개인 개발

버전 : 1.6 (4월) 

목표 : 출시완료 (17.11 ~ 17.12)

플랫폼 : 안드로이드

장르 : 모바일 기반 미니게임 모음 팬게임

개발툴 : Unity, C#, 비주얼스튜디오

링크 : https://youtu.be/xEv2w678O6s


__시스템 특징__

미니게임 전략패턴

전략 패턴을 사용하여 각 게임을 제작. 


블록판정

BFS를 이용하여 블록 판정


GPGS 연동

구글 계정을 연동하여 데이터 보존 및 리더보드를 기록하여 경쟁심리 유도


이펙트 및 사운드

EffectManager와 SoundManager를 자체 제작하여 효과 출력. ParticleSystem과 AudioSource를 활용



### 프로젝트 명 : 블러드루비

팀 프로젝트 (3명) - 기획, 서버, 클라이언트

버전 : 습작 (17.03 ~ 17.09) 

담당 : 클라이언트 프로그래머

플랫폼 : 안드로이드

장르 : 탑뷰 AOS 게임

개발툴 : Unity, C#, 비주얼스튜디오, Spine

링크 : https://youtu.be/NenX2ZYC2e0


시스템 특징

AI구현

행동트리를 이용한 AI 구현


Spine 연동

Spine 연동과 이벤트로 애니메이션 출력


스킬관리

스킬구조


버프관리

버프관리


추상 팩토리 패턴

각 병과마다 팩토리 패턴으로 구현



## 5. 기타 프로젝트

### 프로젝트 명 : 눈과 귀와 손이 즐거운 동화이야기

팀 프로젝트 (3명) - 메인 클라이언트, 서브 클라이언트, 기획

버전 : 습작 (17.03 ~ 17.09) 

담당 : 메인 클라이언트

장르 : 탑뷰 AOS 게임

플랫폼 : iPad

개발툴 : XCode, Mac OS X

수상여부 : 학교 내 축전 대상

링크 : https://youtu.be/V4TAwbDGRII



__사용기술__

글자 입력 알고리즘 : 획에 따른 글자 알고리즘 제작, 

페이지저장 : 페이지저장



### 프로젝트 명 : H.I.D.E

팀 프로젝트 (3명) - 기획, 3D 애니메이터, AI 프로그래머, 메인 프로그래머

버전 : 습작 (17.03 ~ 17.09) 

담당 : 메인 프로그래머

플랫폼 : PC

장르 : 1인칭 방탈출 공포 게임

개발툴 : Unity, C#, 비주얼스튜디오

링크 : 


__사용기술__

플레이어 : 플레이어 조작에 대한 FSM 구현

UGUI : UGUI를 이용하여 UI 구현

수상여부 : 한이음 공모전 입선


