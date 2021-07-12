# 변화율 3가지

1)d
2)D
3)시그마

# 평균변화율 [f(b)-f(a)]/(b-a)

순간 변화율 => b와 a가 한없이 가까울때의 변화율,  a라는 점에서의 순간속도

![image](https://user-images.githubusercontent.com/73323188/125217526-d4cff800-e2fb-11eb-9d62-b8ae25ca83b0.png)

증분 h를 무한히 0으로 보낸것

## dx의 의미 => 오로지 독립변수가 하나만 존재할때 d를 사용

## 편미분 => 변수가 여러개일때를 나타냄

# 편미분

바람은 x,y,z,t(시간)에 대한 함수이다 (지역에서의 발마 => 공간이기 때문에 3차원적 위치 필요=> 기본적으로 xyz에 대한 함수다 )

바람의 시간변화율을 생각하기 위해, 시간에 따라 미분해줘야 한다.

u(x,y,z,t)에서 x 방향으로의 바람의 공간적 분표를 보려고 할때, 파셜(라운드)을 사용한다. 이를 x에 대한 편미분이라 함


# 윈드쉬어 =>  라운드u/라운드z => 윈드쉬어

# 시간가속도 라운드u/라운드t => 공간위치는 그대로, 시간에 따른 바람이 어떻게 변하는가를 본다.

# 어떤 함수 z = f(x,y)일때

![image](https://user-images.githubusercontent.com/73323188/125219427-ace29380-e2ff-11eb-9e1c-635fbe51db82.png)

# 전미분

u(x,y,z,t) x,y,z,t모두를 고려하여 변화율을 보고 싶을때 사용한다

풍선이 예가 될 수 있다. => u(x,y,z,t) 일때, 암시적으로 풍선이 위치(xyz는 시간의 함수 x(t),y(t),z(t)이다.)

![image](https://user-images.githubusercontent.com/73323188/125219856-98eb6180-e300-11eb-9938-289f3210af40.png)

![image](https://user-images.githubusercontent.com/73323188/125223299-7e1beb80-e306-11eb-96ea-09cf5a4da669.png)

DT는 각 방향에 대한 편미분으로 표현할 수 있다. 

# 보존 방정식의 종류 
1) 질량 보존 법칙
2) 운동량 보존 법칙
3) 에너지 보존 법칙

![image](https://user-images.githubusercontent.com/73323188/125224137-f636e100-e307-11eb-9a48-b54c13bd8301.png)

제어체적(control volume) = 방정식을 적용할 대상


# 오일러 & 라그랑지안

제어체적을 어떤식으로 역할을 기술하는가는 2방법이 있다.

![image](https://user-images.githubusercontent.com/73323188/125224532-c76d3a80-e308-11eb-8597-1bdb95c7ba1f.png)

![image](https://user-images.githubusercontent.com/73323188/125224571-d6ec8380-e308-11eb-85da-40085a94920b.png)


1) 오일러 => 제어체적 박스가 이동하지 않는다. 고정 박스면을 통해서 박스로 들어가는 flux(속)가 얼마나 출입하는가 (AWS 백엽상?)
__오일러계에서는 편미분만 있으면 된다.(xyz가 고정되어있기 때문)__


2) 라그랑지안 => 제어체제가 이동함 (라이오존데 풍선이동) / 제어체적을 따라가면서 받는 플러스를 고려하면서 보존방정식을 세

우는것

__전미분 필요.xyz가 변함 이때 xyz는 시간에 대한 함수이다.__

