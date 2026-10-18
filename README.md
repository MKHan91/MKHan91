<!-- Header: Capsule Render + Typing SVG -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F0E6CE,100:D8C09A&height=220&section=header&text=Myungkyu+Han&fontSize=44&fontColor=FFFFFF&fontAlignY=35&desc=Computer+Vision+Research+Engineer&descAlignY=55&descSize=18&descColor=FFFFFF" width="100%" alt="Myungkyu Han | Computer Vision Research Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=Noto%2BSans%2BKR&weight=600&size=20&pause=1100&color=FFFFFF&center=true&vCenter=true&width=760&height=55&lines=%EB%AC%B8%EC%A0%9C%EB%A5%BC+%EC%A0%95%EC%9D%98%ED%95%98%EA%B3%A0%2C+%EB%AA%A8%EB%8D%B8%EC%9D%84+%EC%84%A4%EA%B3%84%ED%95%98%EA%B3%A0%2C+%EC%8B%A4%EC%A0%9C+%ED%99%98%EA%B2%BD%EC%97%90%EC%84%9C+%EB%8F%99%EC%9E%91%ED%95%98%EA%B2%8C+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4.%3BComputer+Vision+%C2%B7+Model+Optimization+%C2%B7+Edge+AI" alt="컴퓨터 비전과 엣지 AI를 연구하는 비전 연구원" />
  <p>
    <a href="https://canva.link/twtbxo2iz9q4z46"><img src="https://img.shields.io/badge/Portfolio-View-2C5364?style=for-the-badge&logo=canva&logoColor=white" alt="Portfolio" /></a>
    <a href="mailto:audrbz@naver.com"><img src="https://img.shields.io/badge/Email-Contact-444444?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.youtube.com/shorts/XccgTKKbucs">
    <img src="https://img.shields.io/badge/Technical%20Video%201-Watch-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Technical Video 1" />
  </a>
  <a href="https://www.youtube.com/watch?v=2fPdZYzx9Cg">
    <img src="https://img.shields.io/badge/Technical%20Video%202-Watch-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Technical Video 2" />
  </a>
  </p>
</div>

---

## 👋 소개

산업용 AI, 의료 AI, 증강현실(AR), 모바일 실시간 추론 분야에서 **7년 이상의 경험**을 쌓아 온 컴퓨터 비전 연구 엔지니어입니다.

단순히 모델을 학습하는 데 그치지 않고, **현상을 분석해 문제를 정의하고, 적합한 모델을 설계하며, 실제 환경에서 동작하도록 최적화하는 과정**에 집중합니다.

## 🚀 주요 성과

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>⚡ 7–8 ms</strong><br />
      Galaxy S9 모바일 CPU 인물 분할 추론<br />
      <sub>모델 크기: 0.20 MB</sub>
    </td>
    <td width="50%" valign="top">
      <strong>📈 1.89× faster</strong><br />
      다중 시점 3D 자세 추정 파이프라인<br />
      <sub>56 FPS → 106 FPS</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>🧠 −50.5% Parameters</strong><br />
      경량 단안 깊이 추정 모델<br />
      <sub>GFLOPs 58.7% 감소, 정확도 유사 수준</sub>
    </td>
    <td width="50%" valign="top">
      <strong>🏆 KITTI Benchmark #1</strong><br />
      단안 깊이 추정 연구 성과<br />
      <sub>2019년 3월–9월 기록</sub>
    </td>
  </tr>
</table>

<sub>성과 수치는 이력서와 포트폴리오에 기재된 결과이며, 기기 및 평가 환경에 따라 달라질 수 있습니다.</sub>

## 🧩 주요 프로젝트

### 01 · 초경량 인물 분할 | Mobile Computer Vision
- 모바일 CPU 실시간 처리를 위한 경량 CNN–Transformer 하이브리드 모델 설계
- 데이터 수집·라벨링, TensorFlow 학습 파이프라인 구축
- FP16 양자화를 적용한 TFLite 변환 및 평가 웹 앱 구현

`Python` `TensorFlow` `TFLite` `C++` `Docker`

**결과:** Galaxy S9 추론 7–8 ms · 모델 0.20 MB

### 02 · 다중 시점 3D 자세 추정 | Sports Analytics
- 4개 카메라 기반 보정 및 DLT 삼각 측량
- 시점별 자세 추정 결과 융합
- 멀티프로세싱과 TensorRT를 통한 처리 파이프라인 최적화

`Python` `PyTorch` `MMPose` `YOLO` `TensorRT`

**결과:** 56 FPS → 106 FPS · 처리 속도 1.89배 향상

### 03 · 모바일 AR 발 검출 | On-device AI
- ShuffleNetV2 기반 경량 인코더–디코더 설계
- 발 키포인트와 분할 마스크 멀티헤드 예측
- 경계 영역 데이터 증강 및 6-DoF 자세 추정용 C++ 구성 요소 구현

`Python` `TensorFlow` `TFLite` `C++`

### 04 · 단안 깊이 추정 및 시맨틱 분할 | Research
- 단안 깊이 추정 및 다중 스케일 팽창 합성곱 기반 시맨틱 분할 연구
- 깊이 추정 논문 공동 저자, 시맨틱 분할 논문 제1저자
- KITTI Depth Prediction Benchmark 1위 기록(2019년 3월–9월)

[관련 코드: BTS — From Big to Small](https://github.com/cleinc/bts)

### 05 · 경량 자기지도 단안 깊이 추정 | Model Efficiency
- 경량 모듈 및 로컬 특징 표현 연구 지도
- Lite-Mono 대비 파라미터·연산량·정확도·추론 속도 비교

**결과:** 파라미터 50.5% 감소 · GFLOPs 58.7% 감소 · Jetson Orin Nano 8GB에서 추론 속도 46–52% 향상

## 🔬 그 밖의 AI 경험

- **산업용 AI:** 전류·진동·음향 데이터 기반 설비 고장 진단, 잔여수명(RUL) 예측, 이상 탐지
- **의료 AI:** 12유도 심전도(ECG) 이미지 기반 부정맥 분류 및 멀티 GPU 학습 인프라
- **기술 교육:** 카메라 인식과 장애물 회피를 다루는 입문용 자율주행 강의 제작

## 🛠️ Tech Stack

**Languages**  
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />

**AI / Deep Learning**  
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" />

**Computer Vision / Deployment**  
<img src="https://img.shields.io/badge/TFLite-4285F4?style=flat-square&logo=google&logoColor=white" /> <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white" /> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />

## 📚 논문

- **From Big to Small: Multi-Scale Local Planar Guidance for Monocular Depth Estimation** — 공동 저자 · [코드](https://github.com/cleinc/bts)
- **Semantic Segmentation with Multi-scale Dilated Convolution of Dense Structure** — 제1저자 · 2019 한국로봇종합학술대회 발표

## 🤝 함께 이야기 나눠요

컴퓨터 비전 기술이 실험실을 넘어 실제 환경에서 가치를 만들 수 있도록, 문제 정의부터 모델 설계와 최적화·배포까지 연결하는 일을 좋아합니다.

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,100:0F2027&height=120&section=footer" width="100%" alt="" />
</div>
