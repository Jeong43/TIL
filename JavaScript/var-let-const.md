# var의 특징
- 함수 레벨 스코프(Function-level scope)
함수의 코드 블록만을 스코프로 인정한다. 따라서 전역 함수 외부에서 생성한 변수는 모두 전역 변수이다. 이는 전역 변수를 남발할 가능성을 높인다.
for 문의 변수 선언문에서 선언한 변수를 for 문의 코드 블록 외부에서 참조할 수 있다.

- var 키워드 생략 허용  
암묵적 전역 변수를 양산할 가능성이 크다.

- 변수 중복 선언 허용  
의도하지 않은 변수값의 변경이 일어날 가능성이 크다.

- 변수 호이스팅  
변수를 선언하기 이전에 참조할 수 있다.


# var, let, const 차이점은?
- `var`는 `function-scoped`이고, `let`, `const`는 `block-scoped`이다.
- `let`과 `const`의 차이점은 변수의 `immutable` 여부이다.  
`let`은 변수에 재할당이 가능하지만, `const`는 변수 재선언, 재할당 모두 불가능하다.

 
# Reference
- https://80000coding.oopy.io/e1721710-536f-43f2-823b-663389f5fbfa
- https://www.howdy-mj.me/javascript/var-let-const/
- https://poiemaweb.com/es6-block-scope
- https://velog.io/@bathingape/JavaScript-var-let-const-%EC%B0%A8%EC%9D%B4%EC%A0%90
