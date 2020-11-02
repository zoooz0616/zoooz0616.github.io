Mid Term 컴퓨터공학과 20180993 이은지
----------------------

개발 환경 소개
===============

```
* 데이터 베이스 : MYSQL
MYSQL은 전세계적으로 가장 널리 사용되고 있는 db이며 다양한 언어를 위한 api도 제공하고 어느 os에서도 사용이 가능하다. 또 크기가 큰 데이터 집합도 빠르고 효과적으로 처리가 가능하다.
물론 mariadb도 장점이 많지만 mysql를 많이 사용해봤고 더 익숙했다. kaggle에서 다운 받은 데이터를 db에 저장시킬 때 mariadb를 사용하는 것보다
mysql workbench를 이용하면 import하기 더 편리했고 구조를 쉽게 볼 수 있기 때문에 mysql을 선택했다. 
```
```
* 웹 서버 : Windows 웹 서버(Bitnami 사용)
윈도우는 전 세계에서 시장점유율을 90%이상 차지한다. 리눅스가 오픈소스로 무료이며 개발하기 더 편하지만 윈도우가 사용자에게 가장 최적화가 잘 되어있고
CLI기반인 리눅스에 비해 windows는 GUI로 명령의 입력이 아닌 클릭으로 여러 기능을 수행할 수 있다. 또 노트북에는 이미 윈도우가 설치되어있기 때문에 바로 사용이 가능했지만 리눅스를 사용하려면 vmware를 사용헤야했다. 하지만 내 노트북이 감당을 하지 못하기 때문에 윈도우를 선택하였다.

```
```
* 백엔드 언어 : PHP
수업시간에 학습한 언어로 다루기 쉬웠고, 웹 개발에 특화된 언어로 다른 언어보다는 직관적으로 코드를 작성할 수 있어
코드가 간단하고 HTML 문서에 적합하여 사용하였다.
```
```
* 프론트엔드 언어 : HTML, CSS
웹 페이지를 제작하기 위해 HTML언어를 사용했고 스타일이 필요한 부분에는 CSS를 적용시켰다.
```

사용한 데이터
=============
* https://www.kaggle.com/rsrishav/youtube-trending-video-dataset

* 매일 업데이트되는 YouTube 인기 동영상 데이터 세트를 사용하여 유튜브 트렌드를 분석하였다.


발견한 정보
==============
1. 유튜브에 업로드된 모든 영상들을 조회수 순으로 정렬. => 요즘 트렌드를 알기 쉬움.
<img src="https://user-images.githubusercontent.com/53183320/97819865-a0c52180-1cee-11eb-82fd-01c08a709a50.PNG">
2. 영상 카테고리별로 분류. => 자신이 관심있는 카테고리의 트렌드를 접할 수 있음.
<img src = "https://user-images.githubusercontent.com/53183320/97819906-e8e44400-1cee-11eb-89b4-e13dbd6c7656.PNG">
<img src = "https://user-images.githubusercontent.com/53183320/97819907-ebdf3480-1cee-11eb-8a84-7d46e6cfb77c.PNG">
3. 키워드 검색 기능. => 자신이 찾고 싶은 키워드를 검색하면 영상의 태그를 검색해 사용자가 입력한 키워드를 포함하고 있는 영상들을 보여줌.
<img src = "https://user-images.githubusercontent.com/53183320/97819931-09140300-1cef-11eb-8ec6-36ade42e09a5.PNG">
<img src = "https://user-images.githubusercontent.com/53183320/97819932-09ac9980-1cef-11eb-9889-63274ff75a8b.PNG">

<동작 영상>
----------
https://youtu.be/9VInSnPQBrA