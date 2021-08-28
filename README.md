# RFID를 이용한 식당혼잡도 안내 및 소독 확인 서비스

## **제안 배경**
코로나 19 확산 가능성이 높은 음식점의 이용을 보다 안전하게 돕기 위한 서비스

<br>

## **서비스 목적**
- RFID 태그를 이용한 음식점 혼잡도 확인 및 알코올 센서를 이용한 소독 여부 확인
- 사용자에게 제공하여 집단 감염 최소화
- 음식점을 운영하는 가게에 상권 유지 도움

<br>

## **기능**
- 음식점 혼잡도 서비스 제공 <br>
: RFID 태그를 이용하여 사용자에게 실시간 음식점 혼잡도를 제공
- 음식점 소독 확인 서비스 제공 <br>
: 알코올 센서를 이용하여 사용자에게 실시간으로 소독 확인 여부를 제공
- 안심 음식점 정보 서비스 <br>
: 공공데이터포털에서 제공하는 안심식당정보 데이터를 활용하여 사용자에게 실시간으로 안심 심당 정보 서비스 제공

<br>

## **기술 스택**
- Server(OpenPaaS 플랫폼인 NHN 토스트 파스-타 이용)
- NodeJs, Express(반응형 웹 애플리케이션)
- H/W(아두이노 MCU, RFID, 알코올 센서)
- 공공데이터(안심식당정보)

<br>

## **기대 효과**
1. 손님 입장
- 안전한 식당 이용 가능
- 다른 사람들과의 접촉 최소화

2. 가게 입장
- 안심 식당 이미지 형성과 홍보 효과
- 고객 만족도를 높이는 효과

---

## **실행 화면**
### **웹 페이지**
음식점 검색 및 지도 페이지

![image](https://user-images.githubusercontent.com/48669011/131219967-beee2b30-fac8-4025-9daf-c8883c4822c7.png)

식당 상세 정보 페이지(방문자 수, 소독 시간, 잔여 좌석)

![image](https://user-images.githubusercontent.com/48669011/131219988-af97ca66-fecb-4831-92dd-5e14e7f4c35d.png)

### **반응형 웹 페이지**
음식점 검색 및 지도 페이지

![image](https://user-images.githubusercontent.com/48669011/131219819-40588872-0fb7-4976-a1d1-1f518eb50f8b.png)


식당 상세 정보 페이지(방문자 수, 소독 시간, 잔여 좌석)

![image](https://user-images.githubusercontent.com/48669011/131219862-1d333f46-157f-4587-97d5-b63c67c59c50.png)
