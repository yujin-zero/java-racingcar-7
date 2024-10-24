# java-racingcar-precourse

# 자동차 경주

## 기능 목록

### 사용자 입력 기능

#### 자동차 이름 입력 기능
- [ ] 사용자는 쉼표를 기준으로 구분하여 여러 가동차 이름을 입력할 수 있다. 
- [ ] 이름이 5자를 초과하는 경우 `IllegalArgumentException`을 발생시키고 애플리케이션을 종료한다.
- [ ] 이름을 중복하여 입력하는 경우 `IllegalArgumentException`을 발생시키고 애플리케이션을 종료한다.

#### 이동 횟수 입력 기능
- [ ] 사용자는 자동차의 이동 횟수를 입력할 수 있다.
- [ ] 입력된 값이 0 이상의 정수가 아닌 경우 `IllegalArgumentException`을 발생시키고 애플리케이션을 종료한다.

### 게임 진행 기능

- [ ] 입력받은 횟수만큼 게임을 반복하여 진행한다.
- [ ] 각 자동차의 전진 여부를 결정하기 위해 0에서 9 사이의 무작위 값을 생성한다.
- [ ] 무작위 값이 4 이상일 경우 해당 자동차의 이동 횟수를 1만큼 증가시킨다.

### 실행 결과 출력 기능
- [ ] 각 라운드가 종료될 때마다 자동차의 이름과 이동 횟수를 출력한다.
- [ ] 게임 종료 후 우승자를 쉼표로 구분하여 출력한다.

