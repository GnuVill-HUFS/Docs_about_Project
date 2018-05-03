#프로젝트에 필요한 프레임워크 & 라이브러리

---



## 원활한 진행을 위해 반드시 git 사용법 숙지해주세요



## 백엔드

> Python3 + Django Web Framework 로 진행한다는 가정하에 읽으면 됩니다.



#### <반드시 팀원 전체가 Python3을 숙지하였다는 가정하에 진행한다>

#### <모르는건 반드시 선 검색 후 질문>



### 라이브러리

* requests

  > rest-api 사용에 있어서 핵심적인 라이브러리


* BeautifulSoup

  > request를 통해 크롤링한 데이터를 파싱하는데 쓴다 
  >
  > > parser: lxml 사용

* json

  > rest-api 요청결과를 json으로 받아야함

* sqlite3

  > 랭킹결과 DataBase 구현

* os

  > 디렉토리 세부 설정에 필요

  ​



### 프레임워크

* Django

  > ```
  > 자주 쓰이는 모듈
  >
  > from django.shortcuts import render
  > from django.http import JsonResponse
  > from django.views.decorators.csrf import csrf_exempt
  > ```






## 프론트엔드

* HTML
* CSS
* JavaScript (Vue.js)









