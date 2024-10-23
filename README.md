# java-racingcar-precourse

## 기능 요구 사항

---

### 자동차 생성
- [x] 자동차의 이름을 쉼표로 구분지어 생성하기
- [x] 각 자동차의 이름은 5자 이하만 가능하며 초과 시 IllegalException 발생 후 애플리케이션 종료 시키기

### 이동 횟수 입력
- [x] 사용자는 몇 번의 이동을 할 것인지를 입력 받기 - 양수만 입력이 가능하며 음수일 경우 IllegalException 발생 후 애플리케이션 종료 시키기

### 자동차의 전진 조건
- [x] 사용자의 이동 횟수 동안 각 자동차는 0~9 사이의 랜덤 숫자 생성하기
- [x] 생성된 랜덤 숫자가 4 이상(4~9)일 경우 자동차는 전진하며, 4미만(0~3)일 경우에는 전진하지 못하게하기

### 자동차 위치 출력
- [x] 매번 이동 시마다 현재 위치를 이름과 함께 출력하기

### 우승자 출력하기
- [x] 자동차들 중에서 가장 멀리 간 자동차를 우승자로 출력하기(우승자는 1명 이상 가능)
- [x] 우승자가 여러명일 경우 쉼표로 구분지어 출력하기
