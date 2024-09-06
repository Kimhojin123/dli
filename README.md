# 동아리 김호진

b> Getting Started with AI on Jetson Nano
![JN](https://github.com/user-attachments/assets/fe20fc0a-1525-46f9-8ba9-e2a88ef74877)

```
 1. Jetson Nano 준비물
  
        - jetson nano
  
        - c type power adapter
  
        - 와이파이 동글
  
        - 웹캠(USB Camera), 또는 CSI Camera (라즈베리파이 V2)
  
        - 64기가 이상 마이크로sd카드
  
        - 그외 쿨링펜, lcd, 또는 모니터. hdmi

 ```

<b> 2. jetson nano에 대하여

<b>  welcome 부터 따라하기
       https://learn.nvidia.com/courses/course?course_id=course-v1:DLI+S-RX-02+V2&unit=block-v1:DLI+S-RX-02+V2+type@vertical+block@aba5104413ae454c8c63a6f301925337

<b> 3. jetpack downloads

  
<b>      https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write

<b> 4. 이미지  굽기 위해 필요한 것들![JN (2)](https://github.com/user-attachments/assets/fef127fe-eebd-4a11-a7ae-3ed51554b7bf)
![스크린샷 2024-09-06 155420](https://github.com/user-attachments/assets/e14db7d4-32ed-46b6-a12c-e2eebaea405d)

    4-1. sd card formatter  download
    4-2. balenaetcher download --->  이미지 굽기
    4-3. 제슨나노에 sd넣고 우분투 설치
![JN (3)](https://github.com/user-attachments/assets/01bbfa32-523d-4f22-aad5-42800424f3ee)

     
 ![스크린샷 2024-09-06 155502](https://github.com/user-attachments/assets/285f4821-a56b-4b85-bf91-307bf0543090)


![스크린샷 2024-09-06 155550](https://github.com/user-attachments/assets/88a2b0e9-6344-41ae-b74c-bf21f3cb08e2)


<b>4. 제슨 알아보고 설치하기
  
  [https://developer.nvidia.com/embedded/learn/jetson-nano-2gb-devkit-user-guide#id-.JetsonNano2GBDeveloperKitUserGuidevbatuu_v1.0-DeveloperKitSetup](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write)

<b> 5. image classification  -  Thumbs Project  using ResNet

  https://learn.nvidia.com/courses/course?course_id=course-v1:DLI+S-RX-02+V2&unit=block-v1:DLI+S-RX-02+V2+type@vertical+block@aabe204272214ba69309581d388b0734

  <b> 5. image regression  -  Face XY Project

  https://learn.nvidia.com/courses/course?course_id=course-v1:DLI+S-RX-02+V2&unit=block-v1:DLI+S-RX-02+V2+type@vertical+block@76a2873eb69946b4928c4f8432e04314

<b>6.terminal열기 

![스크린샷 2024-09-06 160644](https://github.com/user-attachments/assets/ae96992f-e40e-42f1-88c8-b129eb9c6c13)

<b> 7. dli@dli-desktop:~$sudo apt-get upgrade, sudo apt-get update 입력하기 
 7-1`.dli@dli-desktop:~$ sudo apt install python3-pip 입력하기 
 7-2.  컴퓨터가  do you want to continue ? Y 이렇게 물어본다.
 7-3. dli@dli-desktop:~$  sudo -H pip3 install -U jetson-stats라고 친다. 


<b> 8. 쿨링팬 돌리기
   8-1 sudo sh -c 'echo 128 > /sys/devices/pwm-fan/target_pwm'명령어 입력



![스크린샷 2024-09-06 161925](https://github.com/user-attachments/assets/9d9825ef-dafb-4d3d-88db-f89700de5e58)

<b> 9. 카메라 
   9-1. dli@dli-desktop:~$  ls /dev/vi*카메라 인식 확인 명령
   9-2. 영상찍기 

![20240906_161241](https://github.com/user-attachments/assets/720c9de1-9c77-4291-9a5a-03fea131979c)
![스크린샷 2024-09-06 162347](https://github.com/user-attachments/assets/fac684be-55f6-40c7-ab5a-b025b9535f1c)
