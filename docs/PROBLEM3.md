## 🚀 기능 요구 사항

배달이가 좋아하는 369게임을 하고자 한다. 놀이법은 1부터 숫자를 하나씩 대면서, 3, 6, 9가 들어가는 숫자는 숫자를 말하는 대신 3, 6, 9의 개수만큼 손뼉을 쳐야 한다.

숫자 number가 매개변수로 주어질 때, 1부터 number까지 손뼉을 몇 번 쳐야 하는지 횟수를 return 하도록 solution 메서드를 완성하라.

### 제한사항

- number는 1 이상 10,000 이하인 자연수이다.

### 실행 결과 예시

| number | result |
| --- | --- |
| 13 | 4 |
| 33 | 14 |

---

## 📚 정리

3, 6, 9 게임  
1 ~ 10,000 범위의 number가 주어짐  
1부터 number까지 손뼉 총 몇 번?

### ❗ 제한사항  
number의 범위는 1 ~ 10,000    

### ✅ 생각해보기
1. 1부터 number 범위의 for문 사용
2. 각각의 값을 자릿수로 나누고, 3, 6, 9에 해당하는지 확인  
=> 해당된다면 그 갯수만큼 answer 변수에 값 추가 (+=)