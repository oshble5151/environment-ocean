# 델타연산자  => 유체 흐름과 분포를 수학적으로 표현하는데 필요한 미분연산자

# 그래디언트 => 기상장의 3차원 경도 (기울기, 변화율을 표현한것)

# 텔타

![image](https://user-images.githubusercontent.com/73323188/126860833-db4b3153-ce62-4b2a-934b-23160d8aeb1a.png)

델연사자가 붙으면 스칼라가 벡터가 된다.

i,j,k는 각 방향에서의 단위벡터, 이 각 단위 벡터에 미분연산자가 붙어있는 형태이다

예시)
![image](https://user-images.githubusercontent.com/73323188/126860916-c4623d5d-1b32-4639-b128-f001897fc04e.png)

델연산자의 가장 큰 활용 그래디언트를 계산할때 사용된다.

# 그래디언트 => 기상장의 3차원 변화율 (기울기, 변화율을 표현한것)
## 그레디언트를 계산할때의 델연산자는 반드시 스칼라에 적용되야한다.
## 미분 연산이기 때문에, 어떠한 함수가 들어와야한다.(x,y,z,t)

## 필드란? => (x,y,z,t)와 같은 물리량 
## 즉 델연산자는 필드에 결합되서 물리량에 변화를 주는 연산  

![image](https://user-images.githubusercontent.com/73323188/126861006-1d8ff0b9-da75-48eb-8f86-65f18d62c3fd.png)

즉 i방향 f의 변화, j방향 f의 변화, k방향 f의 변화


# 발산

발산의 경우는 델연산자에 벡터가 들어가야 한다.

즉 델연산자에 내적으로 벡터 붙이는 것은 바람의 발산을 의미한다.

![image](https://user-images.githubusercontent.com/73323188/126861088-ebe43b85-f204-4b46-86d1-a48b2743db3f.png)

이를 다이벌젼스(발산) f라고 한다

다이벌전스는 델연산자와 벡터를 내적으로 결합을 해서 스칼라를 얻는 것이다 

## 기상학에서 의 발산과 수렴
## 1) 발산 : 한지점에서 공기가 빠져나가는 것 공기가 빠져나가려면 위에서 하강운동이 생김
## 2) 수렴 : 한지점으로 공기가 모이는 것 공기가 몰리면 상승운동이 생기는 이유 

# 1) x방향으로의 발산을 나타낸 모식도
![image](https://user-images.githubusercontent.com/73323188/126861422-ddd5bfd9-c9bd-4848-b140-26806f2fd382.png)


# 2) y방향으로의 발산을 나타낸 모식도
![image](https://user-images.githubusercontent.com/73323188/126861623-c3eb1346-3469-4426-899e-bbe870156a69.png)

들어오는 양보다 나가는 양이 많으면 제어체적 기준으로 발산이다.



# 회전(curl)

델연산자와 외적으로 정의됨

curlF = 델연산자에 외적F

# 회전계산법

![image](https://user-images.githubusercontent.com/73323188/126861741-691c7e95-3725-4c0c-8a72-6ffea6137c59.png)

# y방향으로 갈수록 세지는 바람 모식도

![image](https://user-images.githubusercontent.com/73323188/126861802-f625f9fc-9eea-454e-85ae-ff65c44d209f.png)

시계방향회전을 북반구에서는 고기압성 소용돌이라고 한다.

# x방향으로 갈수록 세지는 바람 모식도

![image](https://user-images.githubusercontent.com/73323188/126861850-2b4cdc30-7520-4173-9a83-faddec6b044d.png)

북반구 기준, 반시계방향 회전 = 저기압성 소용돌이

![image](https://user-images.githubusercontent.com/73323188/126861882-16565b8c-bcd2-4423-b0f1-e6f4a0f52ff9.png)

# k앞의 물리량의 의미
![image](https://user-images.githubusercontent.com/73323188/126861918-61163965-ddb3-4247-ac88-704e2a747c12.png)

바람의 분포에따라 어떻게 회전이 성립하는가를 의미

이 물리량이 클수록, 저기압성 회전을 한다.

## 지구상에서는 수평면에서의 회전이 중요하다


# 라프라시안 

![image](https://user-images.githubusercontent.com/73323188/126862212-a4332bb6-b4eb-4e15-9c79-147583e3dae2.png)

## 미분을 2번하는 것은 기울기의 변화율을 의미하며, 기울기의 변화율은 곡률을 의미한다.

20분부터 다시

![image](https://user-images.githubusercontent.com/73323188/126862141-7dc3964b-5a9c-434c-98d4-d3ab8bf2646a.png)
