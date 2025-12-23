# Kinematics
### [2025 2학기 로봇알고리즘 과제2]

### 개발 기간
> 2025.09.29 ~ 2025.10.01

### 개발 환경
> Unity 6000.2.1f1<br>
> Templates : Universal 3D<br>
> RTX4050 Laptop<br>

### 설명
+ 동기
  + 로봇알고리즘 수업 과제
+ 기획
  + 2-Link Manipulator
    + 두 개의 관절, 두 개의 링크로 구성된 로봇
    + Configuratrion Parameter : $\theta_1$, $\theta_2$
    + 두 개의 Slider로부터 각 관절의 각도값 $\theta_1$, $\theta_2$를 매 프레임 마다 가져와 Manipulator의 자세를 제어
    + 유니티의 오브젝트 계층 구조를 이용하여, 첫 번째 관절의 각도에 따라 두 번째 관절을 회전하는데 영향을 주도록 함
  + Manipulator X
    + 세 개의 관절, 세 개의 링크로 구성된 로봇
    + Configuration Parameter : $\theta_1$, $\theta_2$, $\theta_3$
    + 첫 번째 관절의 Y축 회전으로 팔의 방향을 결정, 나머지 두 관절의 Z축 회전으로 직렬 조작기 동작을 구현함
  + UAV
    + 세 개의 회전축, 세 개의 이동축을 가짐. 즉, 6자유도(6-DOF)를 가짐.
    + Configuration Parameter : $x$, $y$, $z$, $\theta_x$, $\theta_y$, $\theta_z$
    + 유니티는 왼손 좌표계를 가짐. $z$축은 독자적으로 회전하는 반면 $x$, $y$축은 $z$축에 종속되어 회전함<br><br>

#### 2-Link Manipulator 실행결과

https://github.com/user-attachments/assets/7767ea99-027e-46cb-87a5-36f31269b375

#### Manipulator X 실행결과

https://github.com/user-attachments/assets/c7e2517c-e325-45b4-ad96-b9418df18fbe

#### UAV 실행결과

https://github.com/user-attachments/assets/cab89a3b-f696-4213-800e-c5430f9c976e

<br>
