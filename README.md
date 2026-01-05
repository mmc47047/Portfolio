# 김영교 포트폴리오

> 김영교(Youngyo Kim) 포트폴리오

## 👋 소개

<markdown-accessiblity-table data-catalyst=""><table>
  <tbody><tr>
    <td width="70%">
      안녕하십니까.<br>전기전자공학을 전공하며 임베디드 시스템을 중심으로 하드웨어와 소프트웨어를 연결하는 개발 경험을 쌓아온 김영교입니다.<br><br>MCU로 LED를 제어하고 센서를 연동하며, 코드 한 줄이 실제 하드웨어 동작으로 이어지는 과정에서 임베디드 시스템의 매력을 느꼈습니다. 이후 회로 동작, MCU 제어, 리눅스 BSP, 통신 구조를 학습하며 임베디드를 단순 제어 기술이 아닌 하드웨어·네트워크·AI가 융합된 종합 시스템 기술로 이해하게 되었습니다.<br><br>프로젝트에서는 맡은 역할을 끝까지 책임지는 태도를 바탕으로 문제의 원인을 분석하고, 실제 환경에서 동작하는 시스템을 구현하는 데 집중해 왔습니다. 특히 RC카 주행 제어 프로젝트와 V2X 기반 차량 통신 프로젝트를 통해 센서·통신·제어·ROS2를 아우르는 시스템 통합 경험을 쌓았습니다.<br><br>앞으로도 펌웨어부터 임베디드 리눅스, Edge AI까지 폭넓은 기술 스택을 기반으로, 현장에서 신뢰받는 임베디드 엔지니어로 성장하고자 합니다.
    </td>
    <td width="30%" align="center">
      <img src="assets/화이트.jpg" width="180"></a>
    </td>
  </tr>
</tbody></table></markdown-accessiblity-table>

## 🛠️ 기술 스택
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python) ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java) ![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics) ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino) ![Raspberry%20Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=raspberrypi) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git)


### 🔹 Programming Language
- **C / C++**
  - MCU 제어 및 센서 데이터 처리 펌웨어 구현
  - UART, PWM 등 주변장치 제어 경험
- **Python**
  - 데이터 처리 및 간단한 AI·Edge AIoT 알고리즘 구현
  - ROS2 노드 개발 및 시스템 연동

### 🔹 Embedded / Hardware
- **Arduino / Raspberry Pi**
  - 센서 인터페이스 구성 및 시리얼 통신 구현
  - GPIO 제어 기반 IoT 프로토타입 제작
- **STM32 (CubeMX / CubeIDE)**
  - 핀맵·클록 설정 및 HAL 기반 펌웨어 개발
  - UART, PWM 등 주변장치 설정 및 디버깅 경험

### 🔹 OS / Platform
- **Linux (Ubuntu)**
  - 터미널 기반 개발 환경 구축
  - gcc / make 활용한 빌드 경험
  - BSP 실습을 통한 OS 구조 및 파일 시스템 이해

### 🔹 AI / Robotics / Vision
- **ROS2**
  - Topic 기반 메시지 통신 구조 설계
  - ROS2 노드 및 브리지 노드 개발 경험
- **OpenCV**
  - 영상 처리 및 객체 인식 전처리
- **Edge AI**
  - 임베디드 환경에서 AI 모델 활용 및 시스템 연동 경험

### 🔹 Communication / Network
- **UART / Bluetooth**
  - Raspberry Pi ↔ STM32 간 통신 인터페이스 구축
- **UDP Multicast**
  - V2X 이벤트 수신 및 데이터 전송 구현
- **IoT / AIoT**
  - 센서·네트워크·AI가 결합된 시스템 설계 경험

### 🔹 Tools & Collaboration
- **Git / GitHub**
  - 형상 관리 및 협업 기반 프로젝트 수행
- **Docker**
  - 개발 환경 컨테이너화 및 실행 자동화
 
### 📡 QoS-Aware Autonomous Mobile Mesh Relay System (대표 프로젝트)

>재난·통신 음영 환경에서 통신 품질 저하를 감지하면
>중계 로봇이 스스로 이동하여 메시 네트워크를 복구하는 자율 중계 시스템
>
> * 개발기간 : 2025.11 ~ 2026.01
> * 핵심 역할 : 통신 품질(TQ/RSSI) 기반 연결 인식 내비게이션 알고리즘 설계, BATMAN-ADV 메시 네트워크 상태를 ROS2 제어 루프에 연동
> * Language : Python, C/C++
> * Skill : ROS2, BATMAN-ADV, Linux Networking, TurtleBot3, Raspberry Pi, Qt
> [프로젝트 상세 페이지](https://github.com/mmc47047/Relay_Bot/tree/main)

---

### 🚗 AlphaCar

> 주변 상황 인식 및 위험 예측 기반 스마트 자동차 시스템  
>
>   * 개발기간 : 2025.09 ~ 2025.10  
>   * 핵심 역할 : 멀티캐스트 통신, 시스템 자동화 스크립트, ROS2 기반 시스템 통합  
>   * Language : Python, C/C++  
>   * Skill : ROS2, Docker, CARLA Simulator, Raspberry Pi, 멀티캐스트 통신  
>
> [프로젝트 상세 페이지](https://github.com/mmc47047/alphacar/blob/main/README.md)

---

### ☕ Study Cafe Manager

> IoT 기반 스터디카페 좌석 예약 및 환경 관리 시스템  
>
>   * 개발기간 : 2025.08  
>   * 핵심 역할 : STM32 디바이스 제어, 블루투스 통신 처리, LCD UI 구현, 시스템 통합  
>   * Language : C, Python  
>   * Skill : STM32, Raspberry Pi, Bluetooth(HC-05), MariaDB, Linux, LCD1602  
>
> [프로젝트 상세 페이지](https://github.com/mmc47047/StudyCafeManager/tree/main)

---
 
### 🧠 Desk Manager

> 임베디드 환경 감지 기반 Pomodoro 집중력 관리 시스템  
>
>   * 개발기간 : 2025.08  
>   * 핵심 역할 : FreeRTOS 태스크 설계, Pomodoro 타이머 로직 구현, 센서 인터페이스 및 UI 제어  
>   * Language : C  
>   * Skill : STM32, FreeRTOS, ADC, EXTI, LCD1602, Keypad, Buzzer  
>
> [프로젝트 상세 페이지](https://github.com/mmc47047/DeskManager/tree/main)


## 📬 연락처

- **Email** : kimyoungyo4545@gmail.com  
- **GitHub** : https://github.com/mmc47047
