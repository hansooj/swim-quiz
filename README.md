# 수영 구술 연습 PWA
2급 생활스포츠지도사 수영 구술시험 실전 연습 앱

## 기능
- 규정 2문제 + 지도방법 2문제 = 4문제 1세트 (총 6세트 / 랜덤 조합)
- AI 심사위원 채점 (10점 단위, 10년 경력 전문가 방식)
- 핵심 키워드 포함/누락 표시
- 잘한 점 / 보완할 점 피드백
- 문제 읽어주기 (TTS)
- 음성 말하기로 답변 (STT)
- 다크모드 자동 지원
- 오프라인 사용 가능

---

## 📱 배포 방법 (무료, 약 5분)

### 1단계 — GitHub 올리기
1. https://github.com 가입/로그인
2. 우측 상단 `+` → **New repository**
3. Repository name: `swim-quiz` → **Create repository**
4. **uploading an existing file** 클릭
5. 이 폴더 안의 **모든 파일과 폴더** 드래그앤드롭
6. **Commit changes** 클릭

### 2단계 — Vercel 배포
1. https://vercel.com → **Sign up with GitHub**
2. **Add New Project** → `swim-quiz` 선택
3. 설정 변경 없이 **Deploy** 클릭
4. 약 1분 후 링크 생성 완료! (예: `swim-quiz.vercel.app`)

---

## 📲 홈화면에 설치하는 방법

### iPhone (iOS) — Safari 필수
1. Safari로 링크 접속
2. 하단 공유 버튼(□↑) 탭
3. **홈 화면에 추가** 탭
4. **추가** 탭 → 앱 아이콘이 홈화면에 생성!

### Android — Chrome 권장
1. Chrome으로 링크 접속
2. 주소창 오른쪽 설치 아이콘 탭 (또는 메뉴 → 앱 설치)
3. **설치** 탭

---

## 파일 구조
```
swim-pwa-v2/
├── index.html        ← 앱 전체 (HTML + CSS + JS)
├── manifest.json     ← PWA 설정
├── sw.js             ← 오프라인 지원
├── vercel.json       ← Vercel 설정
├── README.md         ← 이 파일
└── public/
    ├── icon-192.png  ← 앱 아이콘
    └── icon-512.png  ← 앱 아이콘 (대형)
```

## 문제 추가 방법
`index.html` 안의 `ALL_Q` 배열에 같은 형식으로 문제를 추가한 뒤
GitHub에 파일을 다시 올리면 Vercel이 자동으로 업데이트합니다.
