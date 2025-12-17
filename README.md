# X the League - World Seller Race 2026

## 📁 포함된 파일들

### HTML 파일
- `index.html` - 메인 웹사이트 파일

### 이미지 파일 (9개 셀러)
- `china.png` - 중국 대표
- `singa.png` - 싱가포르 대표
- `Japan.png` - 일본 대표
- `mal.png` - 말레이시아 대표
- `thai.png` - 태국 대표
- `indonesia.png` - 인도네시아 대표
- `Vietnam.png` - 베트남 대표
- `korea.png` - 한국 대표
- `USA.png` - 미국 대표

### 배경 이미지
- `sellerrace.png` - "Sell the most, Own the screen" 섹션 배경
- `Startline.png` - 푸터 레이스 트랙 배경
- `flag.png` - 체커 플래그 (현재 미사용, 추후 활용 가능)

---

## 🚀 GitHub Pages 업로드 방법

### Step 1: GitHub 저장소 생성
1. [GitHub](https://github.com)에 로그인
2. 우측 상단 `+` 버튼 → `New repository` 클릭
3. Repository 이름: `xtheleague` (원하는 이름 사용 가능)
4. Public으로 설정
5. `Create repository` 클릭

### Step 2: 파일 업로드
1. 생성된 저장소 페이지에서 `uploading an existing file` 클릭
2. 모든 파일을 드래그 앤 드롭:
   - index.html
   - china.png
   - singa.png
   - Japan.png
   - mal.png
   - thai.png
   - indonesia.png
   - Vietnam.png
   - korea.png
   - USA.png
   - sellerrace.png
   - Startline.png
   - flag.png
3. 하단 `Commit changes` 클릭

### Step 3: GitHub Pages 활성화
1. 저장소의 `Settings` 탭 클릭
2. 왼쪽 메뉴에서 `Pages` 클릭
3. Source: `Deploy from a branch` 선택
4. Branch: `main` 선택, 폴더: `/ (root)` 선택
5. `Save` 클릭

### Step 4: 사이트 확인
- 약 1-2분 후 사이트 주소가 나타남
- 주소 형식: `https://[사용자이름].github.io/[저장소이름]/`
- 예: `https://ashley.github.io/xtheleague/`

---

## 🎨 이미지 교체 방법

### 방법 1: GitHub에서 직접 교체
1. 저장소에서 교체할 이미지 클릭
2. 우측 상단 휴지통 아이콘으로 삭제
3. `Add file` → `Upload files`로 새 이미지 업로드
4. **중요**: 파일명을 동일하게 유지 (예: `china.png`)

### 방법 2: 로컬에서 수정 후 재업로드
1. 모든 파일을 컴퓨터에 다운로드
2. 이미지 파일 교체 (파일명 동일하게!)
3. GitHub 저장소에서 `Add file` → `Upload files`
4. 모든 파일 재업로드 (덮어쓰기 확인)

---

## 💡 주요 기능

✅ **3D 도트 지구본** - Three.js로 실시간 회전 애니메이션
✅ **흑백→칼라 호버** - 마우스 올리면 이미지 칼라로 변경
✅ **플로팅 도시 이름** - 지구본 주변에 떠다니는 애니메이션
✅ **반응형 디자인** - 모바일/태블릿/데스크톱 최적화
✅ **레이싱 테마** - 체커 플래그, 빨강-검정 컬러
✅ **배경 이미지** - 역동적인 레이싱 장면

---

## 🔧 코드 수정이 필요한 경우

### 텍스트 변경
`index.html` 파일을 텍스트 에디터로 열어서 수정:
- "5 MONTHS. 1 STAGE. 1 CHAMPION."
- "WIN 350,000 USD"
- "50K+ followers" → 다른 숫자로 변경 가능

### 이미지 경로
- 모든 이미지는 `index.html`과 같은 폴더에 있어야 함
- 하위 폴더 사용시 경로 수정 필요 (예: `images/china.png`)

### 도시 이름/국가 변경
HTML 파일 하단 JavaScript 부분에서 수정:
```javascript
const countries = [
    { name: 'China', city: 'SHANGHAI', angle: 0 },
    // 여기서 도시 이름 변경 가능
];
```

---

## 📞 문제 해결

### Q: 이미지가 안 보여요
A: 파일명이 정확한지 확인 (대소문자 구분!)
   - `Japan.png` ≠ `japan.png`
   - 모든 파일이 index.html과 같은 폴더에 있는지 확인

### Q: 지구본이 안 돌아가요
A: 브라우저 캐시 삭제 후 새로고침 (Ctrl+Shift+R)

### Q: 모바일에서 레이아웃이 이상해요
A: 반응형 디자인이 적용되어 있지만, 특정 기기에서 문제가 있다면 알려주세요

---

## 🎯 완성!

이제 전 세계 어디서든 접속 가능한 멋진 X the League 사이트가 완성되었습니다! 🏁🎉

사이트 주소를 공유하고, 필요시 이미지만 교체하면 됩니다!
