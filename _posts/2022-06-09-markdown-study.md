---
title: "마크다운 연습"
excerpt: "md 파일에 마크다운 문법 예제를 연습하고 포스트로 업로드 해보자"

categories:
    - Blog
tags:
    - [Blog, Markdown]

toc: true
toc_sticky: false

date: 2022-06-11
last_modifed_at: 2022-06-11
---


<!-- Heading -->
# Heading1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## 헤딩 2 아래에는 수평선이 자동으로 추가

paragraph
paragraph

<!-- Line -->
___
언더스코어 세 번으로 라인 추가  

___

<!-- Text attributes -->
This is the **bold**  text and this is the *italic* text and let's do ~~strikethrough~~.
별 두개로 감싸면 **볼드체**
별 하나로 감싸면 *이탤릭체*
물결 두개로 감싸면 ~~취소선~~

<!-- Quote -->
> Don't forget to code your dream.
>> 인용문 안의 인용문?
>>> 인용문 안의 인용문 안의 인용문?
>>>> 끄아아앙
>>>>> 몇개까지
>>>>>> 되나요?
>>>>>>> ??
>>>>>>>> 언제까지?
>>>>>>>>> 안끝나네

<!-- Bullet List -->
Fruits:
* 🍎Apple
* 🍋Lemon
* 별 하나 붙이고 띄어쓰기로 순서 없는 리스트 만들기

Other fruits:
- 🍑Peach
- 🍌Banana
- -로도 만들 수 있다

Animals:
1. Dog 
    - Spitz
      - Pomeranian
      - Jindo Dog
        - White Jindo Dog
        - Black & Tan Jindo Dog
      - Shiba Inu

<!-- Link -->
Click [here](http://www.naver.com)
[구글 바로가기](http://www.google.com)

<!-- Image -->
![image description](https://www.thesprucepets.com/thmb/yAyX-8s4QnQPmErHjrt3kDKGZto=/2750x1833/filters:no_upscale():max_bytes(150000):strip_icc()/calico-cats-profile-554694-03-987c213c5c0447e3acb7082cbf82c7d8.jpg)

![local calico](calico.jpg)

![calico](https://user-images.githubusercontent.com/69240465/173189810-0638d763-6a11-4999-bb60-7dcdb13a538e.jpg)  


<!-- Table -->

|Header|Description|
|--:|:--|
|Cell1|:으로좌우중간정렬가능|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|

|Fruit|Price|Quantity|
|--|:--:|--:|
|Apple|500|30|
|Banana|600|40|
|Grape|400|20|


<!-- Code -->
 To print message in the console, use `console.log('your message')` and ..

 ```js
 console.log('hello world')
 ```

 ```cpp
#include <iostream>
using namespace std;

int main()
{
    int a, b = 3;
    float c = static_cast<float>(a + b);

    cout << c;

    return 0;
}

// 주석이에요
 ```

<!-- New Line -->
# New Line
**Enter키를 두 번 입력**

동해물과 백두산이 마르고 닳도록 

하느님이 보하사 우리나라 만세

<hr>

**문장의 마지막에 공백을 두 번 입력**

동해물과 백두산이 마르고 닳도록  
하느님이 보하사 우리나라 만세

<!-- Styling text -->
# Styling text
```
**this is bold text**
```
**this is bold text**
<br><br>

```
*This text is italicized*
```
*This text is italicized*
<br><br>

```
<sub>This is a subscript text</sub>
```
Hello<sub>This is a subscript text</sub>
<br><br>

```
<sup>This is a superscript text</sup>
```
Hello<sup>This is a superscript text</sup>

<br><br>
# Quoting text
```
Text that is not a quote
> Text that is a quote
```
Text that is not a quote
> Text that is a quote

<br><br>
# Quoting code
```
Use `git status` to list all new or modified files that haven't yet been committed.
```
Use `git status` to list all new or modifed files that haven't yet been committed.

<br><br>
# Links

```
This site was built using [GitHub Pages](https://pages.github.com/).
```

This site was built using [GitHub Pages](https://pages.github.com/).
