# 마크다운

- markdown은 텍스트 기반 마크업 언어
- 2004년에 만들어짐
- 깃헙 저장소 READEME.md 에서 접할수 있음
- 별도의 도구 없이 텍스트로 작성
- 다양한 형태로 변환 가능
- 단점: 표준이 없다. 

## 문법

# Heading 1 <h1>
## Heading 2 <h2>
### Heading 3 <h3>
 - 제목 등이나 문단 단위에 사용

 Title
 ======

 - 큰 제목

## 인용문구
> 블록 인용
>> 인용 내부  인용
>>> Inner Inner

- 순서가 있는 목록 order
List '<li>'
1. 1번 
2. 2번
3. 3번
## 링크 연결
'[링크 할 내용](링크 주소)
-[naver](https://naver.com)
## 이미지 삽입
`![대체 텍스트](이미지 주소)`
![플레이스홀더](https://via.placehoder.com/150)
## 코드 강조하기
- 백틱(1왼쪽의 물결표시 있는 부분)으로 감싸면 코드 강조`code`

<pre><code>
print("hello")
</code></pre>

- 백틱 3번 사용
```

- 코드 하이라이트(언어표시)
```python
print("hello)
```


| th테이블헤더 | th | th |
| --- | --- | --- |
| th테이블내용 | th | th |


- [마크다운 테이블 생성기]


## 수평선 긋기 `<hr>`

<hr>

---
(dash * 3)
***
(asterisk * 3)
___



## 줄바꾸기 `<br>`
- 줄바꿈 <br>다음줄<br>다음줄<br>
- 줄바꿈 공백  줄변경 안됨 표준에 따라 다름

## 강조 `<strong>`

- **강조**하기
- *이탤릭* 기울이기 `<i>`
- ~~취소선~~
- <u>밑줄</u>긋기
 