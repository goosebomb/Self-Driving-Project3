## 다목적 서비스 로봇
> Multiple Service Robot
**주요 코드는 set에 있습니다.**

## 1. 제작기간
- 2023.3 ~ 2023.6

## 2. 담당업무
- 프로그램

## 3. 사용언어 / 운영체제
- ROS Melodic (C++)
- Python
- Ubuntu 18.04

## 4. 제작
- 각 센서들과의 통신에 Publisher & Subscriber를 사용했습니다.
- 안드로이드, 웹과의 통신을 위해 Firebase를 사용했습니다.
- Firebase는 파이썬의 firebase_admin 패키지를 사용했습니다.
- 외부 충격에 의한 로봇 움직임을 rviz에 반영하기 위해 imu센서를 사용했습니다.
- 프로그램 동작 순서를 위해 enum을 사용했습니다.
- 장착되는 모듈에 맞게 프로그램이 변경되도록 동작 순서를 나누었습니다.
- 층 변환을 적용시키기 위해 rviz 상에서 맵 변환이 이루어지도록 하였습니다.

## 5. 평가
- 동아리에서 진행한 마지막 팀 프로젝트입니다.
- 마지막 프로젝트여서 제작하는 로봇에 여러 기능을 추가해보려고 했습니다.
- rviz에서 다른 맵 불러오기, imu센서에서 받은 yaw값으로 정확한 각도 회전 구현하기, rviz에서 외부충격에 의한 로봇 움직임 반영하기, 카메라를 이용한 장애물 감지
- 이 중 1, 3번을 성공하여 로봇에 적용시킬 수 있었습니다.
- 마지막 프로젝트까지 함께 해준 팀원들이 고마웠습니다.
