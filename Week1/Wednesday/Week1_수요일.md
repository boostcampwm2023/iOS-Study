# 가장 기억에 남는 질문
## S029_이준복 
- delegate에서 AnyObject를 채택하는 이유는 무엇인가 ?
    - delegate를 채택하여 구현하는 곳과 delegate를 호출하는 곳에서의 강한 순환참조를 막기 위해 weak 키워드를 사용해야하는데 이 때문에 AnyObject를 채택해주어야 하지만 이는 참조 타입일 때만 발생하는 문제이기 때문에 delegate를 구현하는 곳이 참조타입이냐 아니냐에 따라 달라질 수 있을 것 같다.

# 새로 알게된 것
## S029_이준복 
- 옵셔널 이스케이핑
  - https://babbab2.tistory.com/164
- 프로즌
  - https://chibest.tistory.com/99