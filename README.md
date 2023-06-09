<img src="https://img.shields.io/badge/-Java-red"> <img src="https://img.shields.io/badge/-Programmers-%2337485D"> <img src="https://img.shields.io/badge/-BaekJoon-%23D7E2EB">
# 👨🏻‍💻 Algorithm Practice

### 1️⃣ 매일 한 문제 이상을 풀이합니다.
  - 프로그래머스와 백준을 병행하며 풀이합니다.
<br/>

### 2️⃣ 막히거나 스스로의 힘으로 풀지 못한 문제는 블로그에 기록합니다.
  - 다시 풀어볼 문제는 README 파일에 기록해두고, 반드시 다시 풀어봅니다.
  - **다시 풀어볼 문제의 조건**
      - 답을 보고해결한 문제
      - 코드가 너무 지저분하게 작성되어 리펙토링이 필요하다고 느껴지는 문제
      - 정확한 알고리즘으로 푼 것인지 의문이 드는 문제
<br/>

### 3️⃣ 문제를 풀이할 때는 이렇게 합니다.
  - 문제를 보자마자 코드를 작성하지 않고, 20 ~ 30분 정도는 종이와 펜으로 알고리즘을 생각해봅니다.
      - 이 과정에서 30분 이상이 넘도록 알고리즘에 접근조차 못했다면 이건 모르는 문제로 판단하여 코드를 참고합니다.
  - 알고리즘에 대한 생각이 끝났다면, 코드의 흐름을 잡아줄 전체적인 흐름을 주석으로 분리합니다. (step 나누기)
  - 코드 흐름 작성이 모두 끝났다면 코드 구현에 들어갑니다.
<br/><br/>

### 💡 생각을 넓히자!
  - 그래프에서 (x1, y1)과 (x2, y2)가 대각선에 있을 경우는 `Math.abs(x1 - x2) == Math.abs(y1 - y2)`를 만족할 때 대각선에 존재한다.

  - 1차원 그래프의 `index를 Column`으로 `값을 Row`로 사용할 수도 있다. `예를 들어 arr[0] = 1은 (1, 0)을 나타낸다.`

  - 중복제거가 필요한 문제는 문자열 사용을 고려해보자. 입력된 순서 보장을 위해서는 `LinkedHashSet` 사용을 고려.

  - 이전 데이터(1, 2, 3)에서 다음 데이터로 옮길 때, 선택지가 (1, 2, 3) 또는 (3, 2, 1)인 경우에는 LinkedList의 `remove()`와 `removeLast()`를 이용해볼 수 있다.
    - 응용하면 `before(4, 1, 2, 3)`에서 1부터 3까지 데이터를 `after(1, 2, 3)`으로 옮길 때, 1의 index를 찾아서 `int data = before.remove(index)`와 `after.add(data)`를 `before.size > index`일 때 `while`문을 돌려주면 된다.

    - after(3, 2, 1)로 옮기고 싶다면 `int data = before.removeLast()`와 `after.add(data)`를 적절하게 사용해주면 가능하다.

  - **양방향 우선순위 큐**와 같은 기능을 사용하고 싶다면 TreeMap의 `firstKey()`, `lastKey()`, `pollFirstEntry()`, `pollLastEntry()`를 사용하면 구현해볼 수 있다. (중복되는 수도 가능)

<br><br>

<div align="center">
  <h3 align="center">🐤 매일 성장합니다.</h3>

  [![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=rody)](https://solved.ac/rody/)
  
</div>
