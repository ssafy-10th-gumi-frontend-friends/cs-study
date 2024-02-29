## IPv4 ICMP 실습

1. cmd 로 ping 했을때  

![Alt text](image-2.png)

2. 들어가보면

![Alt text](image-3.png)

앞에있는 8바이트만 ICMP 임. 
- 요청이면 type이 8

3. IPv4
![Alt text](image-4.png)

4. Flags  
![Alt text](image-5.png)  
조각화 여부에 따라

5. TTL 
윈도우 128로 지정됨, 하나씩 줄어듬

6. 프로토콜  
![Alt text](image-6.png)  
상위 프로토콜 타입을 알려줌

7.  체크섬
![Alt text](image-7.png)  

8. 출발지, 목적지
![Alt text](image-8.png)

