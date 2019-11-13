---
title: 한글,한컴오피스 무반응, 안켜질때, 실행 안될때 방법
excerpt: 로고 뜨고 무반응일때 대처방법
toc: true
toc_sticky: true
header:
  teaser: /assets/images/bio-photo-keyboard-teaser.jpg
categories:
  - Blog
tags:
  - Blog
  - 한글과컴퓨터
  - 한글
  - 한글무반응
  - 한글실행오류
  - 힌글안켜질때
---

한글과컴퓨터 잘 사용하고계시죠
갑자기 실행이 안될때 해결하는 방법입니다.





<원인>

OS에 visual c++ 2013이 설치되어 있지 않은 상태로 한컴오피스 구동에 필요한 visual c++ 2013을 설치하면 문제 해결 가능

![실행오류메세지](assets/markdown-img-paste-20191114015105293.png)


<해결방법>



## 1. CD/ DVD 나 다운로드 설치 경로에 있는 한글 설치 파일 > INSTALL 폴더 > vcredist_x86.exe 실행하여 설치



1) 제어판 > 프로그램 및 기능 실행

2) Microsoft Visual C++ 2013 Redistributable (x86) 삭제

![그림](assets/markdown-img-paste-20191114015119834.png)


* 단, 삭제 후 해당 항목에 연동된 타 프로그램이 정상 동작을 하지 않을 수 있습니다.



3) PC 재부팅



4) 설치미디어 삽입 > 윈도우 탐색기 > HancomOffice_NEO > INSTALL 폴더 > vcredist_x86.exe 실행하여 설치




![](assets/markdown-img-paste-20191114015141414.png)




 ## 2. Microsoft 홈페이지에서 다운로드 하여 설치


  2014 이하제품 : https://www.microsoft.com/ko-kr/download/confirmation.aspx?id=29
  NEO : https://www.microsoft.com/ko-kr/download/details.aspx?id=40784



<출처>한글과컴퓨터 사이트

![원본링크](https://www.hancom.com/cs_center/csFaqDetail.do?faq_seq=2584)
