#OOP 

**다형성(Polymorphism)**
하나의 메세지에 대해 서로 다른 객체가 각자의 방법으로 응답할 수 있는 기능이다. 메세지를 보내는 객체는 어느 객체가 받을 지 알 필요가 없으며, 받는 객체는 어떻게 응답해야되는 지 알고 있다. 

**[[Encapsulation]] 과의 관계**
Polymorphism은 class차원에서 [[Encapsulation]] 을 구현한 구조이다. 메세지를 보내는 객체는 받는 객체들의 superclass의 interface(public functions)만 알고 있고, 내부 상속구조에 대해 알 필요가 없다. 

**장점**
- 다른 Component의 재사용이 용이하다.
- Component 단위로 모듈화 되어 독립적으로 구현되므로 서로간의 의존성이 획기적으로 감소한다.

**Polymorphism의 구조**
Operation overiding 과 Dinamic binding 으로 구현된다. 
- [[Operation overiding]]
	SubClass 가 SuperClass 의 prototype과 동일한 함수를 재정의 하는 것

- [[Dynamic binding]]
	Runtime 시 포인터 변수가 실제 가리키는 객체 타입의 기준으로 호출할 함수를 결정하는 기능