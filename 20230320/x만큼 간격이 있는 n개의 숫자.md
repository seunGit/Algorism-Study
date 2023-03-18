https://school.programmers.co.kr/learn/courses/30/lessons/12954

### 문제 설명
함수 solution은 정수 x와 자연수 n을 입력 받아, x부터 시작해 x씩 증가하는 숫자를 n개 지니는 리스트를 리턴해야 합니다. 다음 제한 조건을 보고, 조건을 만족하는 함수, solution을 완성해주세요.

### 제한 조건
x는 -10000000 이상, 10000000 이하인 정수입니다. <br>
n은 1000 이하인 자연수입니다.

### 입출력 예 <br>
**x	n	answer <br>**
2	5	[2,4,6,8,10] <br>
4	3	[4,8,12] <br>
-4	2	[-4, -8] <br>

### 풀이
**재석**

```python

```

**승기**

```python

```

**연수**

```python
def solution(x,n):
    answer = [] # 빈 list 선언

    for i in range(1, n+1): # i = 1부터 n까지 반복 실행 (n번), range(n) = n전까지 반복문이 돌기 때문에 n+1 해줘야 함
        answer.append(x*i) 
    return answer

```
