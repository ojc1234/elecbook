# elecbook

전자기학 전자책 프로젝트

# 수학

전자기학을 배울 때 가장 중요한 수학적 요소는
수학이다. 우리는 벡터라는 것을 사용하여 전자기적 인력 척력등을 표현 할 것이고, 특정한 위치에서와 전자기적 힘의 관계를 전기장이라는 벡터장(벡터를 출력하는 함수)로 표현할 것이다.

# 벡터
## 벡터의 정의

$$\{ {<a,b,c> = \vec{v} | a,b,c \in \mathbb{R}} \}$$

전자기학에서 쓰는 벡터의 정의는 여러 실수의 나열 이라고 본다.

---

두가지 중요한 특성이 있다.

1. $$\vec{i}, \vec{j}, \vec{k} 를 각각 <1,0,0>, <0,1,0>, <0,0,1> 로 정의한다.$$
2. $$\vec{v}가 <a,b,c>라고 할 때 \space -\vec{v}를 <-a,-b,-c>로 정의 한다$$

---
## 벡터의 연산 
이러한 정의에 입각해 우리는 여러가지 세로운 연산을 정의 할 것이다.

- 두 벡터의 합(두 벡터의 차)
  $$\vec{a} + \vec{b} $$
- 벡터와 스칼라 사이의 곱
  $$k \cdot \vec{a} $$
- 두 벡터의 dot product
  $$\vec{a} \cdot \vec{b} $$
- 두 벡터의 vector product
  $$\vec{a} \times \vec{b} $$
***
* 두벡터의 덧셈
    $$\vec{a} + \vec{b} = \langle a_x + b_x, a_y + b_y, a_z + b_z \rangle$$
    정의한다

    두 벡터의 뺄셈은 
    $$\vec{a} - \vec{b} = \vec{a} + (-\vec{b}) $$

    로 정의한다.

* 벡터와 스칼라의 곱셈
    $$k \cdot \vec{a} = \langle k \cdot a_x, k \cdot a_y, k \cdot a_z \rangle$$
    정의한다.

* 두 벡터의 내적(dot product)
    $$\vec{a} \cdot \vec{b} = a_x \cdot b_x + a_y \cdot b_y + a_z \cdot b_z$$
    정의한다.

* 두 벡터의 외적(vector product)
    $$\vec{a} \times \vec{b} = \langle a_y \cdot b_z - a_z \cdot b_y, a_z \cdot b_x - a_x \cdot b_z, a_x \cdot b_y - a_y \cdot b_x \rangle$$
    정의한다.