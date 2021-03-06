## 1. 스택의 기본

### 스택 개념

* ![](https://previews.123rf.com/images/meggichka/meggichka1503/meggichka150300074/38199587-%EC%B2%B4%EB%A6%AC-%EC%88%98%EC%B1%84%ED%99%94-%EB%B2%A1%ED%84%B0-%EC%9D%BC%EB%9F%AC%EC%8A%A4%ED%8A%B8-%EB%A0%88%EC%9D%B4-%EC%85%98-%EC%99%80%ED%94%8C-%EC%BD%98-%EC%95%84%EC%9D%B4%EC%8A%A4%ED%81%AC%EB%A6%BC%EC%9D%98-3-%EA%B0%9C%EB%A7%8C-.jpg)



​	위의 그림처럼 맨 밑의 초코 -> 딸기 -> 민트의 순서대로 쌓인다.

​	반대로 먹을 때는 민트 -> 딸기 -> 초코의 순으로 먹을 수 있다.

​	**따라서, 가장 먼저 넣은 초코를 가장 나중에 먹을 수 있는 구조가 스택 구조다.**



### 스택 원리

* 스택은 한쪽만 뚫려 있는 구조이기 때문에 삽입과 추출이 한쪽에서만 진행.
  * 스택에 데이터를 삽입하는 작동(함수로 구현) : push
  * 스택에 데이터를 추출하는 작동(함수로 구현) : pop
  * 스택에 들어 있는 가장 위의 데이터(just 변수) : top

<u>*스택이 엄청나게 클 수는 있어도 무한정 할 수는 없다</u>



* **초기값은 -1로 가정** :  top 값이 비어있다는 의미로 -1 (top 값이 양수라면 스택이 쌓여있다는 의미)
* push - push를 하려면 : top을 한칸 올려서 공간 확보 -> push(커피) -> top을 올리고 -> push(녹차)
* pop - pop을 하려면 : pop으로 뽑아내고(녹차) -> top을 한칸 내리고 -> pop으로 뽑아내고(커피) -> top을 내리고
* 먼저, 스택이 꽉 찾는지 확인 



### 스택의 구현

