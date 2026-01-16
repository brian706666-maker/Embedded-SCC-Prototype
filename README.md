# 🚗 Smart Cruise Control (SCC) Prototype

## 1. 프로젝트 개요 (Overview)
본 프로젝트는 아두이노(Arduino)와 초음파 센서를 활용하여 **PID 제어 기반의 차간 거리 유지 시스템**을 구현한 프로토타입입니다.
단순한 주행을 넘어, 임베디드 시스템의 핵심인 **피드백 제어(Feedback Control)**와 **Fail-Safe(안전 설계)** 로직을 연구하는 것을 목표로 합니다.

## 2. 주요 기능 (Key Features)
- **거리 감지:** 초음파 센서(HC-SR04)를 이용한 실시간 전방 거리 측정
- **가변 속도 제어:** 거리에 비례한 모터 속도 조절 (PID Control)
- **비상 정지:** 통신 오류 및 급발진 방지 알고리즘 (Fail-Safe)
- **상태 모니터링:** 시스템 상태(주행/감속/정지) 시리얼 출력

## 3. 개발 환경 (Tech Stack)
- **H/W:** Arduino Uno, DC Motor Driver(L298N), HC-SR04
- **S/W:** Arduino IDE (C/C++)
