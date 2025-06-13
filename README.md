# GymDiary: 스마트 헬스케어 통합 관리 앱

![inbodycare-banner](https://your-image-link.com/banner.png) <!-- 배너 이미지가 있을 경우 -->

## 📱 프로젝트 개요 (Overview)

**GymDiary**는 사용자의 운동 및 건강 관리를 효율적으로 돕기 위해 개발된 **스마트 통합 헬스케어 앱**입니다.  
OCR을 활용한 인바디 결과 자동 추출 및 저장 기능을 기반으로, 회원-트레이너 간 **커뮤니케이션, 운동 기록, 수업 일정 조율, 출석 확인, 챗봇을 활용한 운동 추천** 등을 하나의 플랫폼으로 통합하였습니다.

## ✨ 주요 기능 (Features)

- 📷 **OCR 기반 인바디 정보 자동 인식 및 Firebase 저장**
- 🧑‍💼 **트레이너-회원 간 1:1 채팅 시스템**
- 🗓️ **수업 일정 조율 기능 (When2Meet 스타일 인터페이스)**
- 📍 **GPS 기반 출석 체크 기능**
- 🏋️ **운동 기록 / 식단 기록 / 운동 루틴 추천**
- 🤖 **Gemini 2.5 기반 AI 챗봇을 통한 운동 상담**
- 🔐 **Firebase Authentication 기반 로그인 시스템**

## 📷 스크린샷

| 인바디 업로드 | 운동 추천 챗봇 | 출석 체크 |
|:---:|:---:|:---:|
| ![inbody](https://your-image-link.com/inbody.png) | ![chatbot](https://your-image-link.com/chatbot.png) | ![attendance](https://your-image-link.com/gps.png) |

## 🔧 기술 스택 (Tech Stack)

- **Android (Java)**
- **Firebase**: Authentication, Firestore, Storage
- **Google ML Kit**: OCR (Text Recognition, Korean)
- **Kakao Maps API**
- **Gemini 2.5 API (Google Generative AI)**
- **FusedLocationProvider**: 위치 기반 서비스
- **Cloud Firestore**: 사용자 데이터, 인바디 기록 저장

## 📂 APK 다운로드

> [📦 Download Latest APK](https://github.com/your-repo/releases/latest)

> 또는 `release/` 폴더 내 `.apk` 파일을 직접 다운로드하세요.

## 🚀 프로젝트 실행 방법

1. `git clone`으로 프로젝트를 복제합니다:
   ```bash
   git clone https://github.com/your-username/InBodyCare.git
   ```
2. Android Studio에서 프로젝트 열기
3. `local.properties`에 다음과 같은 API 키를 설정합니다:
  ```bash
   KAKAO_API_KEY=your_kakao_key
   GOOGLE_MAP_API_KEY=your_google_map_key
   KAKAO_MAP_KEY=your_kakao_map_key
   ```
4. APK 빌드 또는 에뮬레이터 실행
---
## 📌 향후 계획 (Future Works)

- 📊 인바디 측정 결과의 **트렌드 그래프 시각화** 기능 추가
- 🧑‍🏫 트레이너를 위한 **관리자 웹 대시보드** 개발
- 🍽️ Gemini 챗봇을 통한 **개인 맞춤형 식단 피드백** 기능 강화
- ⌚ Google Fit 및 웨어러블 기기와의 **데이터 연동 기능** 구현
- 🧠 AI 기반 운동 루틴 자동 생성 기능

## 🙌 기여 및 문의 (Contribution & Contact)

Pull Request 및 Issues는 언제든 환영입니다.  
프로젝트에 기여하고 싶은 분들은 다음 단계를 따라주세요:

1. 이 저장소를 Fork 합니다.
2. 새로운 브랜치를 생성합니다. (`feature/your-feature-name`)
3. 필요한 변경사항을 커밋합니다.
4. Pull Request를 등록해 주세요!

문의 사항이 있으시면 다음 이메일로 연락 주세요:  
📧 **your.email@example.com**

또는 [Issues 탭](https://github.com/your-repo/issues)에서 직접 이슈를 등록해주세요.

