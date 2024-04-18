마크다운(Markdown)이란?
=======================================
2004년 존그루버에 의해 만들어진 텍스트 기반의 마크업언어이다.

장점
=============
1. 간결함
2. 다양한 형태로 변환이 가능
3. 별도의 도구 필요 X
4. 저장 시 용량 적음
5. 변경이력 확인 가능
6. 지원하는 프로그램과 플랫폼이 다양함

단점
=============
1. 표준 X
2. 표준이 없어 도구에 따라 변환방식과 생성물이 다름
3. 모든 HTML 마크업을 대신하지 못함


2. 마크다운 사용법(문법)
2.1. 헤더Headers
큰제목: 문서 제목

This is an H1
=============
This is an H1
작은제목: 문서 부제목

This is an H2
-------------
This is an H2
글머리: 1~6까지만 지원

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
This is a H1
This is a H2
This is a H3
This is a H4
This is a H5
This is a H6
####### This is a H7(지원하지 않음)

2.2. BlockQuote
이메일에서 사용하는 > 블럭인용문자를 이용한다.

> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
This is a first blockqute.

This is a second blockqute.

This is a third blockqute.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.

This is a H3
List
code
