# 템플릿

### 함수 템플릿
- 함수 템플릿 : 여러 함수를 만들어내는 함수의 틀
- 클래스 템플릿 : 여러 클래스를 만들어내는 클래스의 틀
- 함수 오버로딩을 이용하면 매개변수 리스트가 다른 함수를 정의할 수 있다.
- 템플릿 함수를 이용하면 컴파일러는 클라이언트의 함수 호출 인자 타입을 보고 템플릿 함수의 매개 변수 타입을 결정하여 실제 함수인 템플릿 인스턴스 함수를 만들어 낸다.
- template<typename T> void Print(T a, T b)
- 클라이언트가 직접 타입을 지정하고 명시적으로 함수를 호출할 수 있다.
- 템플릿도 함수처럼 여러 매개변수를 가질 수 있다.
- 함수 템플릿의 매개변수로 타입뿐만 아니라 정수 등도 가능하다.
- 함수 템플릿 특수화는 특수화된 버전의 함수 템플릿을 더 제공한다.
- 컴파일러가 함수 템플릿의 인스턴스를 만들려면 템플릿의 매개변수 타입 객체인 a가 템플릿 함수 정의의 연산을 지원해야 한다.

### 클래스 템플릿
- 클래스 템플릿 : 클래스를 만들어내는 틀이다.
- 단지 함수에서 클래스로 바꾸어진 것이다.
- 이제 정수 뿐만 아니라 실수를 저장하는 객체와 문자열을 저장하는 객체가 모두 필요하다.
- 클래스 템플릿은 클래스를 정의하기 위한 메타 클래스 코드이며, 템플릿 매개변수 인자를 통해 클라이언트가 클래스에 사용될 타입을 결정할 수 있다.
- 컴파일러는 클래스 템플릿을 이용해 실제 클래스를 생성한다.
- 템플릿의 매개변수도 함수의 매개변수처럼 디폴트 매개변수 값을 지정할 수 있다.
- 클래스 템플릿도 특수화가 가능하다.
- 클래스 템플릿 특수화는 함수 템플릿 특수화처럼 일반 버전의 템플릿을 사용할 수 없는 경우나 성능 개선이나 특수한 기능 등을 위해 특수화 버전을 별도로 제공하고자 할 때 사용한다
