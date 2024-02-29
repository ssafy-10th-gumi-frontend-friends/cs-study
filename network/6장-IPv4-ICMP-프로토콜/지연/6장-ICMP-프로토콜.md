# 6장 - 2 ICMP 프로토콜

## ICMP가 하는 일
ICMP internet control message protocol   
인터넷 제어 메시지 프로토콜
- 네트워크 컴퓨터 위에서 돌아가는 운영체제에서 **오류메시지**를 전송받는 데에 주로 쓰인다.
- 특정 대상과 내가 통신이 잘 되는지 확인
- 프로토콜 구조의 Type과 Code를 통해 오류 메시지를 전송받는다. 

## ICMP 프로토콜의 구조
1. Type : 대분류
2. Code : 소분류
3. Checksum : 헤더에 오류가 있는지 없는지 확인하는 값

### Type
- 0번, 8번 : 기본. 8번- 요청, 0번- 응답
- 3번, 11번 : 뭔가 잘못됨. 3번 - destination unreachable 목적지까지 가지 못함, 11번 - time exceeded 목적지까지 갔는데, 응답을 받지 못함, 상대방이 방화벽해놨을때
- 5번 : 보안관련 ICMP redirect 상대방 테이블을 원격지에서 수정할 수 있음.

