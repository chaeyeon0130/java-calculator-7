# java-calculator-precourse

## 💡 기능 구현 목록
### 1. 입력 처리
- [X] `Console.readLine`을 사용하여 덧셈할 문자열을 입력받는다.
- [X] 입력 문자열이 `null`이거나 비어있는 경우, 결과를 `0`으로 반환한다.

### 2. 피연산자 추출
- [X] 기본 구분자 `,` 또는 `:`로 숫자 피연산자를 추출한다.
- [ ] 커스텀 구분자 `//[커스텀 연산자]\n`를 사용하여 숫자 피연산자를 추출한다.

### 3. 덧셈 연산
- [ ] 추출된 피연산자를 모두 더한 값을 결과로 반환한다.

### 4. 예외 처리
- [ ] 음수가 입력된 경우, `IllegalArgumentException`을 발생시킨다.
- [ ] 숫자가 아닌 입력이 들어온 경우, `IllegalArgumentException`을 발생시킨다.