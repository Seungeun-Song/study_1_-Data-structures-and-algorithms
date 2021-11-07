## 재귀 알고리즘이란?

* 양쪽에 거울이 있을 때 거울에 비친 자신이 무한 반복해서 비치는 것 
* or 마트료시카 인형처럼 동일한 작동을 무한적으로 반복하는 알고리즘을 의미

​	![](https://mblogthumb-phinf.pstatic.net/20160115_227/hi_nso_1452817375582g10Mw_JPEG/1.jpg?type=w2)

​	<img src="https://blog.kakaocdn.net/dn/WOvzZ/btqRGqU0RcH/fU9KhKiznrPAjUREvGUnw0/img.png" style="zoom:80%;" />



## 재귀 호출의 개념

* 재귀 호출은 자신을 다시 호출하는 것
  * ex, 마지막 종이 상자가 나올 때까지 여러 개 겹쳐진 상자를 꺼내 마지막 상자에 반지 넣기
  * -> 꺼낸 순서와 반대로 종이 상자를 다시 넣는 예
  * ![](https://github.com/Seungeun-Song/study_1_-Data-structures-and-algorithms/blob/master/img/%EC%9E%AC%EA%B7%80%20%ED%98%B8%EC%B6%9C%EC%9D%98%20%EA%B0%9C%EB%85%90.png?raw=true)
  * **재귀 호출 : 종이 상자를 반복해서 꺼내는 과정과 반지를 넣은 후 종이 상자를 다시 반복해서 넣는 과정**



*for문과 재귀는 유사. 선택사항 - but, 재귀는 로직이 분명하지 않고, 스택에 쌓기 떄문에 시간도 느림.



