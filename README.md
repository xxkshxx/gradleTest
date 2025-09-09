Hello World...




## **인증 문제**
```
원인: 401 Unauthorized, 403 Forbidden
해결:
- HTTP Header Manager에서 인증 정보 추가
- Cookie Manager 설정
- Authorization 헤더 확인
```

### **서버 과부하**
```
원인: 503 Service Unavailable, 응답 시간 급증
해결:
- Thread Group의 사용자 수 줄이기
- Ramp-up Period 늘리기
- 서버 리소스 모니터링