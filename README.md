# 로또
## 진행 방법
* 로또 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

# STEP 1: 문자열 계산기
## TODO 기능목록
* [X] 입력 값이 null이거나 빈 공백 문자일 경우 -> IllegalArgumentException throw
* [X] 사칙연산 기호가 아닌 경우 IllegalArgumentException throw
* [X] 공백 문자열을 빈 공백 문자로 분리하려면 String 클래스의 split(" ") 메소드를 활용한다.
* [X] 단순 덧셈기능
* [X] 단순 뺄셈기능
* [X] 단순 곱셈기능
* [X] 단순 나눗셈기능
* [X] 연산 기호가 2개 이상인 식을 계산하는 기능 구현
* [X] 반복적인 패턴을 찾아 반복문으로 구현한다.

# STEP 2: 로또
## TODO 기능목록
* [ ] 구입금액 입력 받기
* [ ] 로또 번호 정렬해서 출력하기
* [ ] 당첨 번호 문자열 입력받기
* [X] 구입금액에 따라 로또 여러 장 만들기
* [X] 랜덤 로또 1장 만들기
  * [X] 각기 다른 숫자로 6개의 숫자 생성하기
* [ ] 당첨 번호 객체로 변환하기
* [ ] 당첨 통계 계산하기
* [ ] 수익률 계산하기