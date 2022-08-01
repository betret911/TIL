# 복잡도

- 시간 복잡도 : 알고리즘을 위해 필요한 연산의 횟수(작업 시간)
- 공간 복잡도 : 알고리즘을 위해 필요한 메모리의 양

## 시간 복잡도

- 빅오 표기법 : O(N), 함수의 상한만을 나타냄<br>
  <img src="img\big-o-notation.jpg" width= "300">

## 시간과 메모리 측정

- 파이썬 수행 시간 측정 소스코드 예시
  ```py
  import time
  start_time = time.time()

  # 소스 코드
  end_time = time.time()
  print("time :", end_time - start_time)
  ```

  