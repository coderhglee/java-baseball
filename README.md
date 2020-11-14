# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

## 기능 목록
- [ ] Game
    - [ ] 게임의 상태를 관리 한다.
        - [ ] 게임 시작/종료 제어 기능
    - [ ] 게임 숫자 객체
        - [x] 게임 규칙에 맞는 숫자 객체를 정의 한다.
            - 1~9까지의 숫자
        - [ ] 숫자만 입력해야 한다. 문자, 특수문자, 공백 불가
        - [x] 자릿수는 3자리다.
        - [x] 숫자 객체 간 값을 비교 하는 기능
            - [x] 숫자도 같고 자릿수도 같은지 판단
            - [x] 숫자는 같은데 자릿수가 다른지 판단
        - [ ] 가상 혹은 사용자에게 생성된 수를 숫자 객체로 변환 하는 기능
    - [ ] 숫자를 관리한다.
        - [ ] 서로 다른 임의의 번호 3개 생성 하는 기능
        - [ ] 사용자에게 입력 받은 번호를 전달 하는 기능 
    - [ ] 야구 게임 객체
        - [ ] 비교된 값으로, 힌트 혹은 결과를 생성한다.
            - [ ] 같은 수가 같은 자리에 있으면 스트라이크, 다른 자리에 있으면 볼
            - [ ] 같은 수가 전혀 없으면 포볼 또는 낫싱
            - [ ] 숫자를 모두 맞추면 승리
    - [ ] 게임 결과에 따른 제어
        - [ ] 정답이 아니면 다시 사용자에게 메시지를 요청하는 기능
        - [ ] 모두 맞추면 게임을 종료하는 기능
        
- [ ] UI  
    - [ ] 사용자로 부터 입력 받은 행동(숫자)를 전달 한다.
        - [ ] 게임 시작
        - [ ] 게임 완전 종료
    - [ ] 전달 받은 메시지를 사용자에게 보여준다.
    