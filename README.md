# 서비스에 카프카 적용을 위한 '정산 API' 샘플
본 샘플은 카프카 메세지 발행으로 서브 도메인이 어떻게 메세지를 받아서 처리하는지를 이해하는 목적입니다.

# 사전 준비 사항
- 도커 실행 환경
- 도커컴포즈로 Kafka 실행해두기

# 서버 정보
- 포트: 18090

# 전체 샘플 설명
1. 주문 도메인 API 서버 실행
2. **정산 도메인 API 서버 실행 (단순한 메세지 수신)** 
3. 배송 도메인 API 서버 실행 (단순한 메세지 수신)
4. 도커를 이용한 카프카 메세지 발행

# 전체 샘플 흐름
![메세지 발행 및 소비 흐름](doc%2Fimages%2Fflow.png)

# 참고사항
- 도커를 이용한 카프카 실행 및 메세지 발행 방법  