# 제목(header)

# 제목 1(중요도 가장 높음)
## 제목 2
### 제목 3
#### 제목 4
##### 샵 개수에 따라 제목의 크기가 점점 줄어듦🤩

# 문장(Pragraph)
무한도전은 너무나도 재밌다
유재석 노홍철 정형돈 정준하 길 박명수 하하

# 줄바꿈(Line Breaks)
❤️무한도전❤️은 너무나도 재밌다   
(띄어쓰기 두번- 줄바꿈) 

유재석<br> 노홍철<br> 정형돈<br> 정준하<br> 길<br> 박명수<br> 하하

# 강조(Emphasis)
_이탤릭_  (기울기처리)  
**두껍게**  (font-weight: bold)  
**_이탤릭+두껍게_**   
~~취소선~~ (text-decoration: line-through)  
<u>밑줄</u>  (text-decoration :  underline)

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요없는 목록
- 순서가 필요없는 목록
- 순서가 필요없는 목록
   - 순서가 필요없는 목록
   - 순서가 필요없는 목록
- 순서가 필요없는 목록


# 링크(Link)

<a href="https://naver.com">NAVER</a>

[NAVER](https://naver.com)

<a href="https://naver.com"  title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "네이버로 이동!")

<a href="https://naver.com" target="_blank">NAVER</a>

target은 markdown에서 제공X 원래 HTML표기로 써야 함

# 이미지(Images)
링크와 이미지의 차이: 앞에 !가 붙어있느냐의 유무

!가 붙어있으면 사진이 바로 뜨게 됨

![PUPPY](https://images.unsplash.com/photo-1608831540955-35094d48694a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=526&q=80)

[ ]안에 위 형태를 넣고 ()에
주소를 적음   

=> 이미지 누르면 주소로 이동
[![CAT](https://images.unsplash.com/photo-1617112513579-d8755a2c4693?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80)](https://naver.com)

# 인용문(BlockQuote)

: 남의 말이나 글에서 직접 또는 간접으로 따온 문장
(네이버 국어사전)

>  남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네이버 국어사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  
>>> 중중첩된 인용문 3  

# 인라인(inline)코드 강조
백틱(``)기호 사용

CSS에서 `bacgkround` 혹은 
`background-image` 속성으로 요소에 
배경 이미지를 삽입할 수 있습니다.

# 블록(block)코드 강조

<a href="https://google.co.kr/" target="_blank">GOOGLE</a>

이 부분이 실제로 화면에 표시되는 용도로
사용되는 것이 아니라, 순수하게 '코드' 개념으로 입력하고 싶은 경우 

```html
<a href="https://google.co.kr/" target="_blank">GOOGLE</a>

```

```css

.list {
  position:absolute;
  top:40px;
}

```

```javascript
 function birth(){
   let date = '970103';
   return date;
 }
```

terminal에 입력하는 것도 넣을 수 있음
```bash
$ git commit -m 'Study Markdown'
```

개발언어를 사용하는 block코드 강조가 아니라면, plaintext를 통해서 단순하게 텍스트만 불러올 수 있음
```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라만세
```

# 표(table)
행이 있는 만큼 하이푼(--)기호와 
vertical( | )바 넣기

position 속성

값 | 의미 | 기본값
--|--|--| 
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

❤️표 가운데 정렬  
: 하이푼 기호 사이에 : 기호 넣어주기

값 | 의미 | 기본값
:--:|:--:|:--:| 
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

❤️표 오른쪽 정렬  
: 하이푼기호 뒤쪽에 : 기호 한 개 넣어주기

값 | 의미 | 기본값
--:|--:|--:| 
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

무한도전 재미있다 내 인생 예능  
미공개 영상 다 풀어조라!!!

<u>무한도전</u> 재미있다 내 인생 예능<br/>
미공개 영상 다 풀어조라!!!

<span style="text-decoration:underline;">무한도전</span> 재미있다 내 인생 예능<br/>
미공개 영상 다 풀어조라!!!

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>
___
!<img width="300" src="https://images.unsplash.com/photo-1425082661705-1834bfd09dca?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=876&q=80" alt="hamster"/>

# 수평선(Horizontal Rule)

---

***
___








































