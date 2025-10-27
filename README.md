# 💧 WaterTracker – 물 마시기 트래커 앱

## 📱 앱 소개
**WaterTracker**는 사용자의 하루 물 섭취량을 기록하고 목표 달성을 시각적으로 보여주는 SwiftUI 기반 건강 관리 앱입니다.
AI 도구(ChatGPT)를 활용하여 설계와 코드를 협업하며 개발 과정을 체계화하였습니다.

---
## 🎯 주요 기능
| 기능 | 설명 |
|------|------|
| ✅ 목표 설정 | 하루 물 섭취 목표(예: 2000ml) 입력 및 저장 |
| 💦 섭취 기록 추가 | 버튼 클릭 시 일정 양(예: +200ml) 누적 |
| 📊 진행률 표시 | ProgressView 및 원형 그래프로 목표 달성률 시각화 |
| 🕒 시간별 기록 | 마신 시간과 양을 리스트 형태로 확인 가능 |
| 🔁 일일 리셋 | 자정(또는 설정된 시각)에 하루 기록 자동 초기화 |

---
## ⚙️ 기술 스택
| 구분 | 사용 기술 |
|------|-------------|
| 언어 | Swift 5.9 |
| 프레임워크 | SwiftUI |
| 저장 방식 | UserDefaults + Codable 구조체 |
| IDE / 환경 | Xcode 15.3, iOS 17 시뮬레이터 |
| 아키텍처 | MVVM (Model-View-ViewModel) |
| 협업 도구 | ChatGPT (AI 설계 협업) |

---
## 🧩 Swift 프로젝트 구조
```
WaterTracker/
├── WaterTrackerApp.swift
├── Models.swift
├── Storage.swift
├── WaterTrackerViewModel.swift
├── Views/
│   ├── DashboardView.swift
│   ├── HistoryView.swift
│   ├── SettingsView.swift
│   ├── RootTabView.swift
│   └── CircularProgressView.swift
└── Utils/
    └── Date+Format.swift
```
---
## 👨‍💻 개발자 정보
- 이름: 이상진  
- 학번: 20211477  
- 과제명: SwiftUI 기반 물 마시기 트래커 앱  
- 과목: 소프트웨어스튜디오2  
- 제출일: 2025.10
