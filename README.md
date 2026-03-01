# 시대학원 조교관리 시스템 (PWA)

## 📁 파일 구성
```
├── index.html        ← 메인 런처 (앱 진입점)
├── journal.html      ← 조교일지 작성기 v2
├── salary.html       ← 급여관리 프로그램
├── manifest.json     ← PWA 설정
├── sw.js            ← 서비스워커 (오프라인/캐싱)
├── icon-192.png     ← 앱 아이콘 (192x192)
├── icon-512.png     ← 앱 아이콘 (512x512)
└── README.md        ← 이 파일
```

## 🚀 GitHub Pages 배포 방법

### STEP 1: GitHub 계정 만들기
- https://github.com 접속 → Sign up

### STEP 2: 새 저장소(Repository) 만들기
1. 우측 상단 [+] → [New repository]
2. Repository name: `sidae-ta` (아무 이름 가능)
3. Public 선택
4. [Create repository] 클릭

### STEP 3: 파일 업로드
1. 생성된 저장소 페이지에서 [uploading an existing file] 클릭
2. 이 폴더의 모든 파일을 드래그 앤 드롭
3. [Commit changes] 클릭

### STEP 4: GitHub Pages 활성화
1. 저장소 → [Settings] 탭
2. 왼쪽 메뉴에서 [Pages] 클릭
3. Source: [Deploy from a branch] 선택
4. Branch: [main] / [/ (root)] 선택
5. [Save] 클릭

### STEP 5: 완료! (1~2분 후 접속 가능)
```
https://YOUR-USERNAME.github.io/sidae-ta/
```

## ⚠️ 배포 후 수정할 것

### index.html 스프레드시트 링크 수정
`YOUR_SHEET_ID` 부분을 실제 스프레드시트 ID로 변경:
```
스프레드시트 URL에서 /d/ 와 /edit 사이의 문자열이 ID입니다.
예: https://docs.google.com/spreadsheets/d/1aBcDeFgHiJkLm.../edit
→ ID: 1aBcDeFgHiJkLm...
```

## 📱 핸드폰에서 앱 설치
1. 위 URL을 핸드폰 브라우저(Chrome/Safari)에서 열기
2. Android: "홈 화면에 추가" 팝업 자동 표시 → 설치
3. iPhone: 하단 공유(□↑) → "홈 화면에 추가"
4. 홈 화면에 앱 아이콘이 생성됨!
