# 2023 poka science war AI team organization

## :pushpin: Description
Share common codes that are necessary for the model training and backup each models you have trained or gonna.  
make sure to make a private repository.

## :fireworks: Screenshots
TBD

## :hammer_and_wrench: Git
guidance: please put tags below when you commit changes to repository.

1. Commit / PR 컨벤션
    - `Feat` : 새로운 기능 추가
    - `Fix` : 버그 수정
    - `Design` : 디자인 및 UI 수정
    - `Docs` : 문서 (README, 메뉴얼 등)
    - `Test` : 테스트 코드
    - `Refactor` : 코드 리팩토링 (기능 변화 없이 성능 개선)
    - `Style` : 코드 의미에 영향을 주지 않는 변경 사항
    - `Chore` : 빌드, 설정 파일
    - `Comment` : 주석 추가

2. Git 브랜치
    - `main` : 기본 브랜치
    - `develop` : 개발된 기능(feature)을 통합하는 브랜치
    - `docs` : 문서작업 브랜치
    - `feat/[issue_num]-[function name]` : 각 기능별 개발을 진행하는 브랜치
    - `test/[name]` : 테스트용 브랜치

## :lock_with_ink_pen: Pipeline And Deadlines
1. Algorithm Team
    - Find all possible states in bush.
    - Implement greedy agent(+ minimax & alphabeta).

2. AI Team
    - Implement all helper functions for reinforcement learning framework.
    - Find good neural network models and features by training candidates with gameplay data from greedy agents.
    - Train the model by Alphazero method and test its performance.
    - Tune the models & features + Make training framework(especially MCTS) parallelizable to fully utilize GPU resource.
    - Test with further models & features(training agent with score instead of winrate, build a model which predict state in bush, etc).

## :fountain_pen: Authors and assigned works
guidance: please put tags [TODO], [WIP], [DONE] at in front of your assigned work.

AI Team  
  
* [@권은성](https://github.com/narinikes)
  * [DONE] helper func of int&act; add how to index int to action at readme (Repo name: helper_function_betweeen_int_and_ACTION)
* [@김준서](https://github.com/kjs0405)
  * TBD
* [@김준석](https://github.com/junseokkim00)
  * TBD    
* [@김현성](https://github.com/kmhs-ph)
  * TBD    
* [@원요한](https://github.com/Periphanes)
  * [WIP] General Pipeline for recieving 3D states and outputting action and state values    
* [@이윤혁](https://github.com/a-nodi)
  * [DONE] State -> tensor code (Repo name: Preprocessor)  
* [@이태민](https://github.com/idearendil)
  * [WIP] Two agents -> data for training(state, action, value) (Repo name: Collecting_Data_from_GreedyAgents)
* [@최지웅](https://github.com/ChoiCube84)
  * [WIP] State (Type: numpy.ndarray) -> State rotated by 180 degrees (Type: numpy.ndarray)
    - Repo name: RotateState
    - Status: Testing

  * [WIP] State (Type: Game) -> One-hot encoded possible actions (Type: numpy.ndarray)
    - Repo name: PossibleActions
    - Status: Testing

  Algol Team
* [@권찬우](https://github.com/kwoncycle)
  * TBD 
* @이유담
  * TBD    
* [@장래오](https://github.com/leo020630)
  * TBD    

## :books: Documentation
TBD


