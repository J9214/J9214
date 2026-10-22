# Choi Jae-won

### Game Client Programmer | C++ · Unreal Engine

플레이어가 직접 체감하는 전투와 게임플레이 시스템을 구현하는 클라이언트 프로그래머입니다.

기능을 만드는 데서 끝내지 않고, 코드의 역할과 변경 범위를 나누는 방법을 고민합니다.  
문제가 발생하면 실행 흐름을 단계별로 나누고, 로그와 테스트를 통해 원인과 수정 결과를 확인합니다.

---

## Projects

### [ProjectWarrior](https://github.com/NBCGameServerCamp09Team01/PW01)

Unreal Engine 게임과 Spring Boot 웹서버를 연동한 웨이브 방어 액션 팀 프로젝트 (4인)

- 적 웨이브, 플레이 통계, 스킬 해금과 게임 클라이언트·웹서버 연동 담당
- 요청 번호·로그인 세션 확인과 약한 참조로 늦게 도착한 서버 응답에서 클라이언트 상태 보호
- 공통 C++ Gameplay Ability 기반 클래스에서 계정 해금 태그를 확인하는 스킬 해금
- 배포 서버 통합 점검에서 판 종료 처리 순서 문제를 로그로 추적해 수정
- 중간에 넘겨받은 채팅 기능을 명세부터 서버, 게임 UI까지 완성
- 웨이브·통계·스킬 기능의 Unreal 자동화 테스트 15개 작성

### [BABEL TRIGGER](https://github.com/J9214/BABELTRIGGER)

싱글 플레이 TPS 웨이브 슈터 개인 프로젝트

- 기획부터 전투, 무기·탄약, 스킬, 웨이브, 상점, UI, 패키징까지 구현
- DataAsset 기반 무기·스킬 시스템 구성
- 컴포넌트 단위 책임 분리와 모듈식 UI 구현
- NavMesh, 충돌 검사, 최소 거리 검사를 이용한 안전한 웨이브 스폰
- 생성 대기열로 적 생성을 나눠 처리해 100마리 기준 한 프레임의 생성 처리 시간 149ms → 3ms
- 카메라와 총구의 2단 Line Trace를 이용한 조준 보정

### [Paragonia](https://github.com/J9214/Paragonia)

Unreal Engine 기반 멀티플레이 AOS 팀 프로젝트

- Gameplay Ability System 기반 전투 파이프라인 구현
- Gameplay Ability, Gameplay Effect, AttributeSet을 이용한 전투 기능 구성
- RPC와 Replication을 이용한 멀티플레이 상태 동기화
- 타격 대상 전달부터 ExecCalc와 Attribute 반영까지 단계별 디버깅
- Git을 이용한 팀 단위 기능 개발과 코드 리뷰 경험

### [Project D](https://github.com/J9214/Project-D)

Unreal Engine 기반 멀티플레이 TPS 팀 프로젝트

- 캐릭터 커스터마이징과 게임플레이 기능 구현
- Mover와 Motion Matching을 활용한 캐릭터 이동 및 애니메이션 구성
- MetaHuman과 Mutable을 활용한 외형 커스터마이징
- 멀티플레이 환경의 기능 연결과 상태 동기화 경험

---

## Skills

### Language

- C++
- C#

### Game Development

- Unreal Engine
- Gameplay Ability System
- UMG / Common UI
- RPC / Replication
- DataTable / DataAsset
- Motion Matching / Mover
- Unreal Automation Test

### Backend

- Spring Boot
- MySQL / Redis

### Tools

- Git / GitHub
- JetBrains Rider
- Visual Studio
- Notion
- Claude Code

## Problem Solving

자료구조와 알고리즘의 기본기를 꾸준히 학습하고 있습니다.  
백준 문제 풀이를 777일 동안 연속으로 진행했으며, 현재는 알고리즘 스터디를 운영하며 서로 다른 풀이와 접근 방법을 공유하고 있습니다.

[![Solved.ac Profile](https://mazassumnida.wtf/api/v2/generate_badge?boj=dnjs4475)](https://solved.ac/dnjs4475/)

## Study Log

알고리즘 풀이와 개발 과정에서 배운 내용을 기록하고 있습니다.  

[Development & Study Blog](https://nowea.tistory.com/)
