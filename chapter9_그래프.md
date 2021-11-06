## 그래프 구조란?

* 버스 정류장과 여러 노선이 함께 포함된 형태, 또는 링크드인(Linked in)과 같은 사회 관계망 서비스의 연결 등의 형태

* <img src="https://bus.go.kr/image/nBus/nBusMap.png" style="zoom: 25%;" />

* <img src="https://d32gkk464bsqbe.cloudfront.net/2ROgcxIDdMwg1ahusYnQhqQNYas=/1000x600/contents/o/2b9eec9f82718fd24754691a03ed63c12bbcd404.jpeg" style="zoom: 33%;" />



## 그래프의 개념

* 여러 노드가 서로 연결된 자료구조
* 트리와 그래프의 차이 : 트리 -  루트에서 하위 노드 방향으로만 이어짐. 그래프 - 여러 노드가 연결될 수 있음.![](https://github.com/Seungeun-Song/study_1_-Data-structures-and-algorithms/blob/master/img/%ED%8A%B8%EB%A6%AC%EC%99%80%20%EA%B7%B8%EB%9E%98%ED%94%84%EC%9D%98%20%EC%B0%A8%EC%9D%B4.png?raw=true)



## 그래프의 종류

* 무방향 그래프, 방향 그래프, 가중치 그래프



## 깊이 우선 탐색의 작동

* 그래프 순회 : 그래프의 모든 정점을 한 번씩 방문하는 것
* 그래프 순회 방식 : 깊이 우선 탐색(Depth First Search, DFS), 너비 우선 탐색(Breadth First Search, BFS)



## 그래프의 인접 행렬 표현

* 그래프를 코드로 구현할 때, 그림으로 그릴 수 없으니까, 일반적으로 인접 행렬(Adjacency Matrix)를 사용한다.

* ![](https://github.com/Seungeun-Song/study_1_-Data-structures-and-algorithms/blob/master/img/%EB%AC%B4%EB%B0%A9%ED%96%A5%20%EA%B7%B8%EB%9E%98%ED%94%84%EC%9D%98%20%EC%9D%B8%EC%A0%91%20%ED%96%89%EB%A0%AC.png?raw=true)
  - 즉, ab나 ba나 같기 때문에 대칭



## 그래프의 응용

* 비상 연락망 : 친구들의 비상연락망에서 특정한 친구가 연락되는지 확인하는 방법

  ![](https://github.com/Seungeun-Song/study_1_-Data-structures-and-algorithms/blob/master/img/%EB%B9%84%EC%83%81%EC%97%B0%EB%9D%BD%EB%A7%9D.png?raw=true)



* 최소 비용으로 자전거 도로 연결

  ![](https://github.com/Seungeun-Song/study_1_-Data-structures-and-algorithms/blob/master/img/%EC%9E%90%EC%A0%84%EA%B1%B0%20%EB%8F%84%EB%A1%9C.png?raw=true)

