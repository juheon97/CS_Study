### [ARP](https://www.inflearn.com/courses/lecture?courseId=335940&unitId=261918)

## ARP (Address Resolution Protocol)
- ip 주소를 통해 MAC 주소를 알아내는 프로토콜
  - 동일 네트워크 내에 있는 송수신 대상의 IP 주소를 퉁해 MAC 주소를 알아낼 수 있음
- ARP 요청 -> 브로드 캐스트 메시지 전송
- ARP 응답 -> 유니캐스트 (1대1) 메시지 전송
- ARP 테이블 갱신 -> ARP 요청-응답을 통해 알게 된 IP 주소와 MAC 주소의 연관 관계
- ARP는 네트워크 별로 수행된다 