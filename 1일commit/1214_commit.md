# 12/14 **커밋 내용**

---

## 12/14 수**요일**

59번째 커밋

## 4가지 타입의 소스코드는 실행 컨텍스트를 생성한다

### ① 전역 코드

- 전역에 존재하는 소스코드를 말한다. 전역에 정의된 함수, 클래스 등의 내부 코드는 포함되지 않는다

### ② 함수 코드

- 함수 내부에 존재하는 소크코드를 맘ㄹ한다. 함수 내부에 중첩된 함수, 클래스 등의 내부 코드는 포함되지 않는다

### ③ `eval` 코드

- 빌트인 전역함수인 `eval` 함수에 인수로 전달되어 실행되는 소스코드를 말한다

### ④ 모듈 코드

- 모듈 내부에 존재하는 소스코드를 말한다. 모듈 내부의 함수, 클래스 등의 내부 코드는 포함되지 않는다

<aside>
💡 모든 소스코드는 평가하면 실행컨텍스트를 생성한다

</aside>