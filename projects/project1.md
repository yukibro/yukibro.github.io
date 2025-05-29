---
layout: default
title: VR Chat Project
---

# VR Chat Project (with Deep Learning)

## Introduction
기존 VR Chat은 대부분 fullbody pose를 생성할때 Default Sensor인 HMD, L/R Controller에  
추가적인 Sensor를 요구하거나, 추가적인 Sensor의 정보가 충분하지 않으면 IK Solver를 적용해서  
fullbody pose를 생성함.  
추가적인 Sensor(tracker)는 비용문제, 그리고 IK Solver를 사용한 delay 발생으로 인한 한계가 있음.

이를 극복하기 위해 Deep learning-based pose 생성 방식을 사용해  
Default Sensor 만으로 fullbody pose 생성을 하는 VR Chat Project를 제안함.
<br>
<br>
## Pipe Line
여기에 이미지 삽입 해야함
<br>
<br>
## Tech Stack
- Python (PyTorch)
- Unity + SteamVR
- SMPL 모델
- ZeroMQ / TCP 소켓 통신

#### 📎 관련 링크
- [GitHub 저장소](https://github.com/yourname/vrchat-project)
