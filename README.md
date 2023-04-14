# SockJS 테스팅 서버

SockJS 연동 테스트용 스프링부트 서버

### 엔드포인트 
`http://localhost:8080/ws`

### 메시지 발송 
`http://localhost:8080/app/topic`

### 메시지 타입
```json
{
  "name": string
}
```

### 토픽 구독 
`http://localhost:8080/topic/greetings`
