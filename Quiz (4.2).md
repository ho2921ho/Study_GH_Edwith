## (동건)
문제1: 
```
cost = tf.reduce_sum(tf.square(hypothesis - y_train))
````
위 코드에서 잘못된 부분을 찾고, 그 이유를 설명하시오.  

---
문제2:  
gradient descent 학습 알고리즘에서 gradient는 한 지점에서 local minimum으로 가는 최단 방향을 의미한다고 할 수 있다.
그렇다면, learning rate은 무엇을 의미하는가?

---
문제3:  
40명인 한 학급을 대상으로 음악, 미술, 국어, 수학 성적을 통해 EQ(감성지능)을 예측하려고 한다. 
이 때, X의 shape은 어떤 형태이며 아래의 코드에서 ?에 들어갈 숫자는?
```
X = tf.placeholder(tf.float32, shape=[?,?])
W = tf.Variable(tf.random_normal([?, ?]), name='weight')
```
---