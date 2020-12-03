# 미션 - 자동차 경주 게임

## 👍 프로그램 개요
- 우아한테크코스의 프리코스 2주차 과제를 수행하기 위한 레포지토리입니다.
- 자동차 경주 게임을 구현합니다.
  - 경주할 자동차의 이름들을 입력합니다.
  - 진행할 이동(턴) 횟수를 입력합니다.
  - 각 이동(턴)동안 자동차는 **전진**하거나 **멈춰** 있습니다.
  - 모든 이동이 끝나면 자동차 게임 승자를 결정합니다.
- 요구 사항은 [프리코스 과제 저장소](https://github.com/woowacourse/java-racingcar-precourse)를 참고했습니다.

## ✔ 구현할 기능 목록
- 자동차 이름 입력이 올바른지 체크하는 기능
  - 이름은 5자 이하여야 한다.
  - 이름은 중복되면 안 된다.
- 자동차 이름을 매개인자로 Car 객체를 생성해 리스트에 추가하는 기능
- 각 이동(턴)동안 랜덤하게 자동차를 전진시키거나 멈추는 기능
  - 0에서 9사이 random한 값을 바탕으로 4 이상이면 전진 3 이하면 멈춤
  - RandomUtils 사용
- Car 리스트의 객체들이 가진 위치 변수를 비교해 우승자를 리턴하는 기능
  - 공동 우승 가능함
- 예외 상황 시 각 예외에 해당하는 문자열을 리턴하는 기능

## 📝 License

This project is [MIT](https://github.com/woowacourse/java-racingcar-precourse/blob/master/LICENSE) licensed.
