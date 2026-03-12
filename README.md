# 📊 연금 마일스톤 트래커

> 만 52세 → 은퇴 후 연금 수령 로드맵 (2026–2044)
> GitHub Pages + Google Drive 동기화

## 🌐 접속 URL

```
https://[내 GitHub 아이디].github.io/pension-tracker/
```

## 📁 파일 구조

```
pension-tracker/
├── index.html          ← 메인 트래커 웹앱
└── README.md           ← 이 파일
```

## 🔧 GitHub Pages 설정 방법

1. GitHub에서 `pension-tracker` 저장소 생성 (Public)
2. 이 파일들을 업로드
3. Settings → Pages → Source: `main` 브랜치, `/ (root)` 폴더 → Save
4. 약 1~2분 후 `https://[아이디].github.io/pension-tracker/` 접속 확인

## ☁️ Google Drive 동기화 설정

웹앱을 열고 상단 **⚙ 동기화 설정** 버튼을 클릭하면 단계별 안내가 나옵니다.

### 요약
1. [script.google.com](https://script.google.com) → 새 프로젝트
2. `gas_backend.js` 코드를 붙여넣고 저장
3. 배포 → 웹앱 → 액세스: 모든 사용자 → URL 복사
4. 트래커 웹앱에 URL 붙여넣기 → 연결

### 동작 방식
- 완료 처리 시 자동으로 Google Sheets에 저장
- 다른 기기에서 접속 시 자동으로 최신 데이터 불러옴
- 인터넷 없을 때는 브라우저 로컬 저장소 사용
