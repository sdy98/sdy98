# 노약자 도우미


## **1. 블럭도**

![스크린샷(66)](https://user-images.githubusercontent.com/105420733/170254203-b201b56a-5249-462b-9ef7-e47de8cbcc74.png)


## **2. 작품 목표**

- 우리나라가 빠르게 초고령사회에 진입함에 따라 독거노인 수와 노인 고독사는 계속해서 증가할 것으로 보인다. 독거노인의 심박수, 체온과 같은 건강정보를 실시간으로 기록해 위급상황 시 보호자에게 알리고, 구조 요청이 필요할 때 신속한 대처가 가능하도록 하는 시스템을 개발하여 노인 고독사를 예방하는데에 목표를 둔다. 


## **3. 진행사항**

### 12주차

* 웹서버 부분
 >motion을 이용한 라이브 웹스트리밍(웹 카메라 작동 확인)
 
 >motion 설치
 
 > $ sudo apt-get install motion

![Hnet-image](https://user-images.githubusercontent.com/105420733/170521420-48f7b16f-75a5-469e-91fe-d81626b120f0.gif)
 >추후 플라스크 웹서버를 이용하여 웹스트리밍으로 수정
  
### 13주차
  
* 웹서버 부분
  >플라스크 회원가입 및 로그인, 로그아웃 기능
  

https://user-images.githubusercontent.com/105426407/174955130-4b6a3746-82a1-46fb-a1db-bc2438d1f1b5.mp4




https://user-images.githubusercontent.com/105426407/174962552-724bfe53-594c-47e6-a259-14d55df18ba4.mp4




  >데이터베이스 관리 시스템 DBMS((DataBase Management System)을 사용
  
 
  ![2022-06-22-151441_1053x656_scrot](https://user-images.githubusercontent.com/105426407/174958696-fabcdb79-540a-43ea-b400-67c7aa9ad43e.png)
   
  >SQLite를 사용하여 사용자 로그인 데이터베이스 관리
  
 ### 14주차
 
* 웹서버 부분
  > 플라스크 웹서버를 이용하여 웹스트리밍 및 메인 웹서버 연동
>연동전 메인 웹서버
![스크린샷(3)](https://user-images.githubusercontent.com/105426407/174965025-943a2f69-39a6-45a9-b9f0-02331055c8f8.png)

>연동전 웹스트리밍 서버
![2022-06-22-160444_898x666_scrot](https://user-images.githubusercontent.com/105426407/174965947-a393997d-8c84-4798-a249-d136902306cc.png)

>연동

https://user-images.githubusercontent.com/105426407/174966941-1d5e96fb-d2fc-4789-96f1-a05e6b50968f.mp4



* Raspberry Pi Zero W > Arduino Nano RP2040 Connect 로 변경

![사양](https://user-images.githubusercontent.com/105420733/170625585-af5e94cb-bba4-4fac-a0e9-2befb2a7de36.png)



* 웹서버 부분
  > highchart를 이용하여 무작위 값을 받아 flask 웹 서버에 실시간 그래프 그리기 구현
  


https://user-images.githubusercontent.com/105426407/189661083-6a44f2b4-d70a-41ae-bcaa-f911bb8d9640.mp4


> 실시간 영상처리를 이용하여 flask 웹 서버에 실시간 얼굴인식 기능 사용

![스크린샷(8)](https://user-images.githubusercontent.com/105426407/189661648-2213aef7-53dd-46c2-870c-888f1f90c738.png)

flask 웹 서버에서 실시간 영상처리 사용하면 반응속도가 느려짐
