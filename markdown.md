# Markdown

### 마크다운이란?
텍스트 기반의 마크업 언어로 읽고 쓰기 편하게 구성되어있음.  
특수기호와 문자를 활용하여 간단한 구조를 작성할 수 있음.  
HTML과 호환됨.
- markdown 확장팩으로 github 구성으로 사용하면 됨
> 여기선 Markdown Preview Github Styling 이거 사용함!

#### 장단점
장점
1. 간단함
2. 특별한 도구가 필요하지 않음
3. 텍스트로 저장되기 때문에 용량 활용이 높음

단점
1. 표준이 없음
2. 모든 HTML 요소를 대신하지 못함

### 헤더
- HTML Header 요소와 동일한 것으로 문서의 제목을 나타냄  
- h1 ~ h6 까지의 제목을 표현할 수 있음
- '#' 이라는 기호로 헤더를 표시
# Header1 (HTML - h1)
## Header2 (HTML - h2)
### Header3 (HTML - h3)
###### Header6 (HTML - h6)

### 블록 인용
- 인용구를 표현할 때 사용
- '>' 이라는 기호를 사용하여 표현

> 첫 번째 인용구
> > 두 번째 인용구

### 리스트
- 나열된 항목을 나타낼 때 사용
- 순서가 존재하는 리스트(HTML ol), 순서가 존재하지 않는 리스트(HTML ul)
- '1. 숫자.' 기호로 순서가 존재하는 리스트를 표현
- '*', '+', '-' 기호로 순서가 존재하지 않는 리스트를 표현

1. apple
2. banana
3. cherry

- apple
- banana
- cherry

+ apple
+ banana
+ cherry

### 코드
- 코드를 작성하기 위한 영역을 지정
- HTML code 요소와 동일
- '```'(백틱 3개) 기호로 표현

```
public static void main(String args[] args) {
    System.out.println("code");
}
```

- 시작하는 '```' 뒤에 표현하고자 하는 언어를 지정하면 문법 강조를 할 수 있음

```java
public static void main(String args[] args) {
    System.out.println("code");
}
```

### 구분선
- HTML hr 요소와 동일한 것
- 영역을 구분하고자 할 때 사용
- '* * *', '***별별별', '*****별별별별별', '- - -', '------------------' 기호로 표현 가능

***

- - - 

### 링크
- HTML a 요소와 동일한 것
- '[키워드][링크의 구분자]'
- '[링크의 구분자]: url'

[Naver][naverid]  
[네이버][naverid]

[naverid]: https://naver.com

### 텍스트 강조
- 기울임꼴, 굵은글씨, 취소선을 표현
- '*', '_' 기호로 기울임꼴 표현
- '**', '__' 기호로 굵은글씨 표현
- '~~' 기호로 취소선 표현

내가 그린 *기린 그림*은 ~~잘 그린~~ **기린 그림**

### 이미지
- HTML img 요소와 동일한 것
- ![이미지 설명](이미지 경로)

![강아지](https://images.mypetlife.co.kr/content/uploads/2021/06/29144346/shutterstock_1538252027-1024x709.jpg)

### HTML 사용
- 마크다운 대신 HTML 사용 가능

<h2 style="color: yellow">HTML 텍스트</h2>

##### 공식홈페이지: https://www.markdownguide.org/ 

