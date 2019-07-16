https://nolboo.kim/blog/2014/04/15/how-to-use-markdown/

하나 건진 것
javascript 북마클릿 소스 건짐
```
javascript:void(prompt("","["+document.title+"]("+location.href+")"));
```

한글 uri도 잘 뜨도록 수정
```
javascript:void(prompt("","["+document.title+"]("+decodeURI(location.href)+")"));
```
location.href를 디코딩.

uri 인코딩/디코딩 관련 javascript 내장 함수? 소개
https://www.codingfactory.net/10377