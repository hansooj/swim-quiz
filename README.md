# 수영 구술 연습 PWA v7
2급 생활스포츠지도사 수영 구술시험 실전 연습 앱

## 주요 기능
- 200개 고정 문제 풀 (규정 50문제 + 지도방법 150문제)
- 랜덤 출제 버튼으로 세트별 문제 즉시 교체
- AI 새 문제 출제 (매번 다른 문제, 무한 반복)
- AI 심사위원 채점 (10점 단위, 10년 경력 전문가 방식)
- 핵심 키워드 포함/누락 표시
- 잘한 점 / 보완할 점 피드백
- 문제 읽어주기 (TTS)
- 음성 말하기로 답변 (STT)
- 다크모드 자동 지원
- 오프라인 사용 가능 (고정 문제)

---

## 배포 방법 (무료, 약 5분)

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
4. 약 1분 후 링크 생성! (예: `swim-quiz.vercel.app`)

---

## 핸드폰 홈화면 설치

### iPhone (iOS) — Safari 필수
1. Safari로 링크 접속
2. 하단 공유 버튼(□↑) 탭
3. **홈 화면에 추가** 탭
4. **추가** 탭

### Android — Chrome 권장
1. Chrome으로 링크 접속
2. 주소창 오른쪽 설치 아이콘 탭
3. **설치** 탭

---

## 파일 구조
```
swim-v7/
├── index.html      ← 앱 전체 (HTML + CSS + JS)
├── manifest.json   ← PWA 설정
├── sw.js           ← 오프라인 지원
├── vercel.json     ← Vercel 배포 설정
├── README.md       ← 이 파일
└── public/
    ├── icon-192.png
    └── icon-512.png
```

## 문제 추가 방법
`index.html` 안의 `ALL_Q` 배열에 같은 형식으로 추가 후
GitHub에 파일을 다시 올리면 Vercel이 자동 업데이트합니다.
