---
title: "[C++] 객체, 변수, 함수, 식별자의 개념"

categories:
    - C++
tags:
    [C++, 따배씨++]

toc: true
toc_sticky: true

date: 2021-01-03
last_modified_at: 2021-01-03
---

해당 포스팅은 '[홍정모의 따라하며 배우는 C++](https://www.inflearn.com/course/following-c-plus)' 1.3장, 1.5장, 1.6장을 듣고 작성자가 정리한 내용입니다. 

### 객체와 변수
**객체** (Object): 컴퓨터 메모리에 실재하는 것  
**변수** (Variable): 객체의 핸들, 사람이 인식할 수 있는 이름

### L-value와 R-value
메모리 주소를 **프로그래머가 직접 접근할 수 있는가**로 구분할 수 있다.
```cpp
x = 123
``` 
왼쪽의 x는 메모리 주소를 가지는 LV이고, 오른쪽의 123은 일시적으로 존재했다가 사라지기 때문에 주소에 접근할 수 없는 RV이다.


```cpp
x = x + 2;
```
x + 2 에서, x는 변수가 아닌 값으로써 작동하는 RV다.

### 함수
- 함수도 메모리에 올라와 있다.
- 함수의 입력으로 들어와 사용되는(쉽게 말해, 함수 정의에 사용되는) 존재를 **매개변수**(Parameter) 라고 한다.
- 함수를 호출할 때 사용되는 값을 **인수**(Argument) 라고 한다.

### 식별자
**식별자**(Identifier)는 변수, 함수, 객체 등의 이름을 지칭한다.   
변수와 함수의 식별자를 통해 인식하는 것은 **메모리 주소**이다.    


식별자 이름 자체는 프로그래머의 편의를 위한 것이지 프로그램의 런타임에는 전혀 존재하지 않는다.  
컴파일 시에, 모든 식별자는 컴파일러에 의해 메모리 주소로 대체된다.  
식별자가 메모리 주소로 대체되는 과정에 대해 아래 링크에서 더 알아볼 수 있다.  
[stackoverflow - How are variable names stored in memory in C?](https://stackoverflow.com/questions/14612314/how-are-variable-names-stored-in-memory-in-c)