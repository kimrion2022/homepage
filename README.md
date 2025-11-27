# 데이터 사이언티스트 포트폴리오 웹사이트

현대적이고 전문적인 데이터 사이언티스트 포트폴리오 웹사이트입니다. 프로젝트, 기술 스택, 경험을 효과적으로 선보일 수 있도록 설계되었습니다.

## 🌟 주요 기능

### 📱 반응형 디자인
- 모바일, 태블릿, 데스크톱 모든 기기에 완벽하게 대응
- 부드러운 사용자 경험 제공

### 🎨 섹션 구성

#### 1. **네비게이션**
- 스티키 네비게이션바
- 모바일 메뉴 (햄버거 메뉴)
- 부드러운 스크롤 이동

#### 2. **홈 섹션 (Hero)**
- 눈에 띄는 헤더 이미지
- 그래디언트 배경
- Call-to-action 버튼

#### 3. **소개 섹션**
- 프로필 텍스트
- 주요 통계 (완료된 프로젝트, 경력, 만족도)
- 시각적으로 매력적인 카드 디자인

#### 4. **프로젝트 섹션**
- 6개의 주요 프로젝트 소개
- 각 프로젝트별 기술 스택 표시
- 호버 애니메이션 효과
- 상세보기 버튼

#### 5. **기술 스택 섹션**
- 프로그래밍 언어
- 머신러닝/AI 기술
- 데이터 분석/시각화 도구
- 개발 도구/플랫폼
- 스킬 레벨 시각화

#### 6. **연락처 섹션**
- 이메일, LinkedIn, GitHub 링크
- 연락 양식 (이름, 이메일, 메시지)
- 반응형 레이아웃

#### 7. **푸터**
- 저작권 정보
- 소셜 미디어 링크

## 💻 기술 스택

### Frontend
- **HTML5** - 의미론적 마크업
- **CSS3** - 현대적인 스타일링
  - Flexbox & Grid 레이아웃
  - CSS 애니메이션
  - 그래디언트 배경
  - CSS 변수 활용
- **JavaScript (Vanilla)** - 인터랙티브 기능
  - 모바일 메뉴 토글
  - Intersection Observer API
  - 부드러운 스크롤
  - 양식 처리

## 🚀 주요 기능 상세

### 반응형 디자인
```
- 데스크톱 (1200px 이상)
- 태블릿 (768px - 1199px)
- 모바일 (480px - 767px)
- 작은 화면 (480px 이하)
```

### 애니메이션 효과
- **페이드인/아웃**: 섹션 진입 시 요소 등장
- **슬라이드 애니메이션**: 헤로 섹션 텍스트
- **호버 효과**: 프로젝트 카드, 버튼
- **스킬 바 애니메이션**: 스크롤 시 진행률 표시
- **스크롤 이벤트**: 네비게이션 바 강조

### 모바일 최적화
- 터치 친화적 인터페이스
- 큰 터치 영역
- 효율적인 모바일 메뉴
- 최적화된 이미지

## 📋 파일 구조

```
homepage/
├── index.html           # 메인 HTML 파일
├── styles.css           # CSS 스타일 파일
├── script.js            # JavaScript 파일
└── README.md            # 문서
```

## 🎨 색상 팔레트

```
주요 색상: #667eea (보라색)
보조 색상: #764ba2 (어두운 보라색)
강조 색상: #f5576c (핑크)
배경색: #f8f9fa (밝은 회색)
텍스트: #333 (어두운 회회색)
```

## 🔧 커스터마이징 가이드

### 개인 정보 수정
`index.html` 파일에서 다음을 수정하세요:

1. **이름 및 소개**
   ```html
   <h1>데이터로 인사이트를 발견합니다</h1>
   ```

2. **프로젝트 정보**
   ```html
   <div class="project-card">
       <h3>프로젝트 제목</h3>
       <p>프로젝트 설명</p>
   </div>
   ```

3. **연락처 정보**
   ```html
   <a href="mailto:your.email@example.com">your.email@example.com</a>
   ```

4. **기술 스킬**
   ```html
   <div class="skill-item">
       <div class="skill-name">기술 이름</div>
       <div class="skill-level">
           <div class="skill-bar" style="width: 85%"></div>
       </div>
   </div>
   ```

### 색상 변경
`styles.css`의 CSS 변수를 수정하세요:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f5576c;
    /* ... */
}
```

### 새 프로젝트 추가
프로젝트 섹션에 새로운 카드를 추가하세요:

```html
<div class="project-card">
    <div class="project-image" style="background: linear-gradient(135deg, #color1, #color2);"></div>
    <h3>프로젝트명</h3>
    <p>프로젝트 설명</p>
    <div class="project-tags">
        <span class="tag">태그1</span>
        <span class="tag">태그2</span>
    </div>
    <a href="#" class="btn btn-secondary">상세보기</a>
</div>
```

## 🌐 배포 방법

### GitHub Pages
1. 저장소를 공개로 설정
2. Settings → Pages → Source를 main 브랜치로 설정
3. `https://[username].github.io/homepage` 에서 접근 가능

### Netlify
1. Netlify 계정 생성
2. 저장소 연결
3. 자동 배포 설정

### Vercel
1. Vercel 계정 생성
2. GitHub 저장소 임포트
3. 자동 배포

## 📱 브라우저 호환성

- Chrome (최신 버전)
- Firefox (최신 버전)
- Safari (최신 버전)
- Edge (최신 버전)

## 🚀 성능 최적화

- 최소화된 CSS/JavaScript
- 부드러운 애니메이션
- Intersection Observer를 통한 효율적인 렌더링
- 반응형 이미지

## 📞 지원

문제가 있으시면 GitHub Issues를 통해 보고해주세요.

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

---

**마지막 업데이트**: 2025년 11월 27일
