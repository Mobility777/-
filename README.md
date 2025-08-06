# -[README.md](https://github.com/user-attachments/files/21608705/README.md)
# 멘톨 쿨링 선크림 랜딩 페이지

이중 기능성 제품인 멘톨 쿨링 선크림을 소개하는 현대적이고 반응형 웹 애플리케이션입니다.

## 🚀 프로젝트 개요

이 프로젝트는 여름철 야외활동 시 자외선 차단과 동시에 피부 쿨링 효과를 제공하는 혁신적인 멘톨 쿨링 선크림의 랜딩 페이지입니다. 사용자들이 제품의 혜택을 이해하고 체험 신청을 할 수 있도록 설계되었습니다.

## ✨ 주요 기능

- **반응형 디자인**: 모든 디바이스에서 최적화된 사용자 경험
- **현대적 UI/UX**: Tailwind CSS를 활용한 세련된 디자인
- **애니메이션 효과**: 부드러운 전환과 인터랙티브 요소
- **실사용자 리뷰**: 신뢰도를 높이는 고객 후기 섹션
- **제품 체험 신청**: 사용자가 제품을 체험해볼 수 있는 신청 폼
- **관리자 대시보드**: 체험 신청 현황을 관리할 수 있는 관리자 페이지

## 🛠️ 기술 스택

### Frontend
- **React 18.3.1** - 사용자 인터페이스 구축
- **TypeScript 5.5.3** - 타입 안전성 보장
- **Vite 5.4.2** - 빠른 개발 환경과 빌드 도구
- **React Router DOM 7.7.1** - 클라이언트 사이드 라우팅

### 스타일링
- **Tailwind CSS 3.4.1** - 유틸리티 퍼스트 CSS 프레임워크
- **PostCSS 8.4.35** - CSS 후처리기
- **Autoprefixer 10.4.18** - CSS 벤더 프리픽스 자동화

### 아이콘 및 UI 요소
- **Lucide React 0.344.0** - 현대적인 아이콘 라이브러리

### 개발 도구
- **ESLint 9.9.1** - 코드 품질 관리
- **TypeScript ESLint 8.3.0** - TypeScript 전용 린팅

## 📁 프로젝트 구조

```
src/
├── components/           # React 컴포넌트
│   ├── Hero.tsx         # 메인 히어로 섹션
│   ├── Problem.tsx      # 문제점 소개 섹션
│   ├── Solution.tsx     # 솔루션 소개 섹션
│   ├── DevelopmentProcess.tsx  # 개발 과정
│   ├── TargetAudience.tsx      # 타겟 오디언스
│   ├── CompetitiveAdvantage.tsx # 경쟁 우위
│   ├── Testimonials.tsx # 실사용자 리뷰 섹션
│   ├── CTA.tsx          # 행동 유도 섹션
│   ├── ApplicationForm.tsx     # 체험 신청 폼
│   └── AdminDashboard.tsx      # 관리자 대시보드
├── App.tsx              # 메인 앱 컴포넌트
├── main.tsx             # 앱 진입점
└── index.css            # 글로벌 스타일
```

## 🎯 주요 페이지

### 1. 홈페이지 (`/`)
- **Hero 섹션**: 제품 소개와 주요 혜택
- **Problem 섹션**: 기존 제품의 한계점 설명
- **Solution 섹션**: 멘톨 쿨링 선크림의 혁신성
- **Development Process**: 제품 개발 과정
- **Target Audience**: 타겟 고객층
- **Competitive Advantage**: 경쟁 우위
- **Testimonials**: 실사용자 리뷰 및 후기
- **CTA**: 행동 유도 버튼

### 2. 체험 신청 페이지 (`/apply/:type`)
- 제품 체험 신청 폼
- 사용자 정보 입력
- 신청 현황 확인

### 3. 관리자 대시보드 (`/admin`)
- 체험 신청 현황 관리
- 신청자 데이터 확인
- 통계 및 분석

## 🚀 시작하기

### 필수 요구사항
- Node.js 16.0.0 이상
- npm 또는 yarn

### 설치 및 실행

1. **저장소 클론**
```bash
git clone [repository-url]
cd Randing
```

2. **의존성 설치**
```bash
npm install
```

3. **개발 서버 실행**
```bash
npm run dev
```

4. **브라우저에서 확인**
```
http://localhost:5173
```

### 빌드 및 배포

```bash
# 프로덕션 빌드
npm run build

# 빌드 미리보기
npm run preview

# 코드 린팅
npm run lint
```

## 🎨 디자인 특징

### 색상 팔레트
- **Primary**: Cyan/Teal 그라데이션 (시원함과 신뢰성)
- **Secondary**: Yellow/Orange (자외선 차단 강조)
- **Accent**: Green (자연스러운 쿨링 효과)

### 애니메이션
- 부드러운 호버 효과
- 페이드인/아웃 전환
- 플로팅 요소들의 움직임
- 스케일 변환 효과
- 리뷰 카드 호버 애니메이션

### 반응형 디자인
- 모바일 퍼스트 접근법
- 태블릿 및 데스크톱 최적화
- 유연한 그리드 시스템

## 📱 주요 컴포넌트

### Hero 컴포넌트
- 제품의 핵심 가치 제안
- 시각적 임팩트를 위한 애니메이션
- 명확한 행동 유도 버튼

### Problem 컴포넌트
- 기존 제품의 한계점 시각화
- 사용자 페인 포인트 명확화
- 문제 해결의 필요성 강조

### Solution 컴포넌트
- 제품의 혁신적 특징 소개
- 기술적 스펙과 혜택
- 시각적 제품 표현

### Testimonials 컴포넌트
- 실사용자 리뷰 카드 (택배 기사, 대학생, 행사 스태프)
- 별점 시스템과 직업별 아이콘
- 사용자 만족도 통계 (98% 만족도, 10,000+ 사용자, 4.9/5 평점, 95% 재구매율)
- 주요 효과 하이라이트 섹션 (즉시 쿨링, 자외선 차단, 끈적이지 않음)
- 리뷰 작성 유도 CTA

## 🔧 개발 가이드

### 새로운 컴포넌트 추가
1. `src/components/` 디렉토리에 새 컴포넌트 생성
2. TypeScript 인터페이스 정의
3. Tailwind CSS 클래스 활용
4. 필요한 경우 Lucide React 아이콘 사용

### 스타일링 가이드
- Tailwind CSS 유틸리티 클래스 우선 사용
- 커스텀 CSS는 최소화
- 반응형 디자인 고려
- 접근성 가이드라인 준수

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 문의

프로젝트에 대한 문의사항이 있으시면 이슈를 생성해 주세요.

---

**멘톨 쿨링 선크림** - 더위를 식히고 자외선을 차단하는 혁신적인 제품 
