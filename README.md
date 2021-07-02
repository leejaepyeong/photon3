# photon3

![image](https://user-images.githubusercontent.com/80494367/124199186-5611d880-db0d-11eb-8e91-9c36fce72523.png)

![image](https://user-images.githubusercontent.com/80494367/124201354-c8d18280-db12-11eb-9f6f-1c7a61e30dd4.png)

### photon Animator
Discrete  변화가 있을때만
Continous 업데이트 함수처럼 계속

Photon RigidBody
Enable teleport for large distance 일정 거리이상 차이가 발생하면  해당 값만큼 순간이동
velocity / angular 에 대한 동기화도 존재

Photon Transform View
위치 회전 크기에 대한  동기화 여부

Photon Transform View Classic
동기화 속도에 따른 덜덜거리는 현상을 제어 가능
Interpoiate Option의 모드를 Fixed speed로 바꿔서 보간.  고정된 속도로 이동
데이터가 많을때 보간 

Extrapolate Option 데이터가 적을때 보간용


![image](https://user-images.githubusercontent.com/80494367/124201700-a0965380-db13-11eb-9c91-fb1e02ab3e2b.png)

![image](https://user-images.githubusercontent.com/80494367/124201758-c3286c80-db13-11eb-955e-791c78863136.png)


![image](https://user-images.githubusercontent.com/80494367/124201809-ee12c080-db13-11eb-877e-508acd2f0fdd.png)

![image](https://user-images.githubusercontent.com/80494367/124201917-39c56a00-db14-11eb-94b2-eef790402f76.png)


![image](https://user-images.githubusercontent.com/80494367/124201888-274b3080-db14-11eb-9996-7813b744f020.png)

![image](https://user-images.githubusercontent.com/80494367/124201985-61b4cd80-db14-11eb-8e07-40e784f194a1.png)

![image](https://user-images.githubusercontent.com/80494367/124202014-74c79d80-db14-11eb-82ba-df26dd3887e4.png)

![image](https://user-images.githubusercontent.com/80494367/124202083-96c12000-db14-11eb-8b40-cb5e8ebc8846.png)

![image](https://user-images.githubusercontent.com/80494367/124202138-bbb59300-db14-11eb-9386-25b8a5070f4f.png)

![image](https://user-images.githubusercontent.com/80494367/124202217-e30c6000-db14-11eb-8250-26dc97950345.png)


![image](https://user-images.githubusercontent.com/80494367/124203594-071d7080-db18-11eb-932a-68e052911a56.png)
![image](https://user-images.githubusercontent.com/80494367/124203752-624f6300-db18-11eb-9617-80533737d177.png)

방 관리

![image](https://user-images.githubusercontent.com/80494367/124203997-f9b4b600-db18-11eb-95e6-28d38b9beb7a.png)

1번키 (alpha1)을 누르면 IsStart가 반대 상태로 변환 >>  이 값을 isStart로 보내기


![image](https://user-images.githubusercontent.com/80494367/124204625-64b2bc80-db1a-11eb-8eee-7763a109ea3e.png)

싱글톤으로 관리 가능  하나만 존재한다면
sort() actor넘버가 작은 순서대로 정렬 

![image](https://user-images.githubusercontent.com/80494367/124204814-d2f77f00-db1a-11eb-9b23-c37d506917c6.png)

![image](https://user-images.githubusercontent.com/80494367/124205119-8c565480-db1b-11eb-983a-dab5a20457fc.png)


비밀 방
![image](https://user-images.githubusercontent.com/80494367/124205158-9ed08e00-db1b-11eb-81f9-d5d5f1e3e434.png)


![image](https://user-images.githubusercontent.com/80494367/124205262-db9c8500-db1b-11eb-8b37-0e9adc085e86.png)

![image](https://user-images.githubusercontent.com/80494367/124205476-4483fd00-db1c-11eb-8116-67c10a1aed41.png)

![image](https://user-images.githubusercontent.com/80494367/124205553-6ed5ba80-db1c-11eb-8b4b-d51d1f443845.png)

 

![image](https://user-images.githubusercontent.com/80494367/124205777-e9063f00-db1c-11eb-8e71-edc14b83a9fa.png)

Queue<T>
Enqueue(obj) 먼저 들어온 순서대로 내보내기

  ![image](https://user-images.githubusercontent.com/80494367/124205963-574b0180-db1d-11eb-9507-8daf9edc8267.png)

  들어온 순서대로 생성해줌
  
  ![image](https://user-images.githubusercontent.com/80494367/124206111-9da06080-db1d-11eb-82f8-52583a6deff0.png)

  
  포톤채팅

  ![image](https://user-images.githubusercontent.com/80494367/124206973-63d05980-db1f-11eb-9437-d3d715d927a3.png)
  Photon Chat 으로 생성
  ![image](https://user-images.githubusercontent.com/80494367/124207014-777bc000-db1f-11eb-9636-fd39c10ac615.png)
아이디를 App Id Chat 에 붙여넣기 하면 가능
  
  ![image](https://user-images.githubusercontent.com/80494367/124207050-97ab7f00-db1f-11eb-9ae1-5a23d90b7e21.png)

  
   포톤보이스
 ![image](https://user-images.githubusercontent.com/80494367/124209874-5cac4a00-db25-11eb-9621-93d4c14a7b43.png)

 ![image](https://user-images.githubusercontent.com/80494367/124209933-7b124580-db25-11eb-9f4f-c974d88881da.png)

 ![image](https://user-images.githubusercontent.com/80494367/124209950-87969e00-db25-11eb-8c9e-e05d82203891.png)

 ![image](https://user-images.githubusercontent.com/80494367/124210017-a85ef380-db25-11eb-80fc-e2120ea6d1b8.png)
 
 ![image](https://user-images.githubusercontent.com/80494367/124210064-c167a480-db25-11eb-9e4b-c4142639ea09.png)

 ![image](https://user-images.githubusercontent.com/80494367/124210529-89149600-db26-11eb-9bef-12ec6561c386.png)

가까워지면 (서로 트리거발동 ) 하면 사운드 발생

 


