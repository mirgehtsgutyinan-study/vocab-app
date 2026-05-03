# 📚 영단어 암기장 — GitHub Pages 배포 가이드

## 파일 구성
```
vocab-app/
├── index.html      ← 앱 본체
├── manifest.json   ← PWA 설정
├── sw.js           ← 오프라인 지원
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## 🚀 배포 방법 (10분)

### 1단계 — GitHub 계정 만들기
https://github.com 에서 무료 가입

### 2단계 — 새 저장소(Repository) 만들기
1. 로그인 후 오른쪽 위 **+** → **New repository**
2. Repository name: `vocab-app` (원하는 이름 OK)
3. **Public** 선택
4. **Create repository** 클릭

### 3단계 — 파일 올리기
1. 새 저장소 페이지에서 **uploading an existing file** 클릭
2. 이 폴더의 파일들을 전부 드래그앤드롭
   - index.html
   - manifest.json
   - sw.js
   - icons/ 폴더 (안에 icon-192.png, icon-512.png 포함)
3. 아래 **Commit changes** 클릭

### 4단계 — GitHub Pages 켜기
1. 저장소 상단 **Settings** 탭
2. 왼쪽 메뉴 **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** / **(root)** 선택 → **Save**
5. 1~2분 후 `https://[내GitHub아이디].github.io/vocab-app` 으로 접속 가능!

---

## 📱 홈화면 아이콘 추가

### Android (Chrome)
- 앱 주소 접속 → 주소창 오른쪽 메뉴(⋮) → **홈 화면에 추가**
- 또는 앱 하단 배너에서 **설치하기** 버튼 탭

### iPhone / iPad (Safari)
- Safari로 앱 주소 접속
- 하단 공유 버튼(□↑) → **홈 화면에 추가** → **추가**

---

## ✅ 완료!
이제 스마트폰 홈화면에서 앱 아이콘으로 바로 접근할 수 있어요.
인터넷 없이도 작동하고, 데이터는 기기 내에 저장됩니다.
