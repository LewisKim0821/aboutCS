# 변수 호이스팅.
 JavaScript에서 호이스팅(hoisting)이란, 인터프리터가 변수와 함수의 메모리 공간을 선언 전에 미리 할당하는 것을 의미.

인터프리터: 코드를 별도의 기계어 번역과정없이 바로 실행하는 프로그램환경.

컴파일러 언어:자바(JVM) , C언어



타언어(matlab)에서는 함수, 변수등의 선언전 call이 불가.

```
if a ==! b 
    c = a + b ;
end

c

a = 3;
b = 2;

%오류!
```

```
console.log(name); // undefined
var name = 'Lewis';
```

undifined -> name이라는 변수자체는 호이스팅.
하지만 'Lewis'라는 값은 호이스팅 되지않음. 즉 name이라는 변수는 존재하지만 그 값은 존재X (undefined.)


ES6이후 출시된 문법인 let, const는  호이스팅 불가. 
(let - 재선언 불가. 변수 선언된 블록내에서만 호출가능. 

업데이트(블록범위 밖에서 재선언) 가능.

const - 재선언 불가, 업데이트 불가
)

