## 이진 트리 구조

* ![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Binary_search_tree.svg/1920px-Binary_search_tree.svg.png) 
* ex, 회사내 조직도, windows 폴더 ...



## 이진 트리의 개념

* 루트(root) : 트리의 맨 위
* 노드(node) : 트리에서의 각 위치
* 에지(edge) : 노드를 연결하는 선
* 부모 - 자식 관계 : 위 노드와 바로 아래 노드의 관계
* 차수(degree) : 자식 노드의 개수  ex, 8의 차수는 2, 3의 차수는 2, 1의 차수는 0
* 리프(leaf) : 차수가 0인 노드  ex, 1,4,7,13



## 이진 트리의 종류

* 전형적인 이진 트리 = 모든 노드의 자식이 최대 2개인 트리
* 포화 이진 트리 = 모든 노드의 차수가 두 개씩 꽉 차있는 경우
* 완전 이진 트리 = 노드가 일부 비어있어도 되지만 <u>왼쪽부터 오른쪽으로, 위에서 아래로 번호를 부여했을 때 비어있지 않은 경우</u>
* 일반 이진 트리 = 중간 번호의 노드가 비어있을 수도 있는 경우
* 편향 이진 트리 = 오른쪽이나 왼쪽이나, 한쪽으로만 연결된 트리



## 이진 트리의 노드 구조

![](https://media.vlpt.us/images/513sojin/post/6aa50c43-7f11-4ca9-a594-da486feb56af/%EB%A7%81%ED%81%AC%ED%91%9C%ED%98%84.png)


(^ 완전 이진 트리)



## 이진 트리의 순회

* 순회 : 이진 트리의 노드 전체를 한 번씩 방문하는 것
* 자료구조로 데이터를 효율적으로 활용하는 대표적인 방법은 필요한 데이터를 효과적으로 검색하는 것.

* 종류 : 전위 순회, 중위 순회, 후위 순회

* 이진트리의 순회를 구현하는 방식 : 스택(stack), 재귀 함수



## 이진 탐색 트리

* 이진 트리 중 활용도가 높은 트리로, 데이터 크기를 기준으로 일정 형태로 구성

  ![](https://github.com/Seungeun-Song/study_1_-Data-structures-and-algorithms/blob/master/img/%EC%9D%B4%EC%A7%84%20%ED%83%90%EC%83%89%20%ED%8A%B8%EB%A6%AC%EC%9D%98%20%EB%8C%80%ED%91%9C%EC%A0%81%EC%9D%B8%20%ED%98%95%ED%83%9C.png?raw=true)

(^ 일반 이진 트리)



## 이진 탐색 트리의 생성

* 첫 번째 데이터를 최상위 노드로 지정

```
memory = []
root = None

nameAry = ['블랙핑크','레드벨벳','마마무','에이핑크','걸스데이','트와이스']

node = TreeNode()        # 노드 생성
node.data = nameAry[0]   # 데이터 입력
root = node 			 # 첫 번째 노드를 루트 노드로 지정
memory.append(node)		 # 생성한 노드를 메모리에 저장
```



* 두 번째 이후 데이터를 삽입할 때는 이진 탐색 트리의 특징을 고려.

  ```
  name = '주황'					# 두 번째 데이터
  node = TreeNode()			 # 새 노드 생성
  node.data = name			 # 새 노드에 데이터 입력
  
  current = root				 # 현재 작업 노드를 루트 노드로 지정
  if name < current.data:		 # 입력할 값을 현재 작업 노드의 값과 비교
  	current.left = node		 # 작으면 새 노드를 왼쪽 링크로 연결
  else:
  	current.right = node	 # 크면 새 노드를 오른쪽 링크로 연결
  memory.append(node)			 # 새 노드를 메모리에 저장
  ```

  



