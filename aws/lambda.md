# lambda

- callbackWaitsForEmptyEventLoop

```
람다에서의 콜백은 기본적으로는 이벤트 루프 안의 모든 작업이 비워질때까지 콜백이 호출되지 않습니다.
이 속성을 false로 설정하여 이벤트 루프에 이벤트가 있더라도콜백이 호출 된 직후 프로세스를 중지하도록 람다에 요청할 수 있다.
```
