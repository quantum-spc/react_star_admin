# React Star Admin

React Star Admin은 React와 다양한 UI 라이브러리를 활용한 관리자 대시보드 템플릿 프로젝트입니다.  
깔끔한 디자인과 다양한 컴포넌트, 차트, 폼, 테이블, 인증 페이지 등을 제공합니다.

## 주요 특징

- **대시보드**: 방문자, 전환율, 매출 등 다양한 지표를 시각화하는 차트와 통계 위젯 제공
- **UI 컴포넌트**: 버튼, 드롭다운, 폼 요소 등 기본 UI 컴포넌트 다수 내장
- **테이블**: 데이터 표시를 위한 반응형 테이블 컴포넌트
- **차트**: Chart.js, react-chartjs-2 등 다양한 차트 라이브러리 지원
- **아이콘**: Material Design Icons 등 다양한 아이콘 사용 가능
- **다국어 지원**: i18next 기반의 다국어(영어/아랍어 등) 지원
- **인증 페이지**: 로그인, 회원가입 등 사용자 인증 관련 페이지 제공
- **에러 페이지**: 404, 500 등 에러 페이지 내장
- **반응형 레이아웃**: 데스크탑/모바일 환경 모두 대응
- **설정 패널**: 테마 및 기타 설정을 위한 사이드 패널 제공

## 폴더 구조

- `src/app/dashboard` : 대시보드 관련 컴포넌트
- `src/app/basic-ui` : 버튼, 드롭다운 등 기본 UI 컴포넌트
- `src/app/form-elements` : 폼 요소 관련 컴포넌트
- `src/app/tables` : 테이블 컴포넌트
- `src/app/charts` : 차트 컴포넌트
- `src/app/icons` : 아이콘 컴포넌트
- `src/app/user-pages` : 로그인, 회원가입 등 인증 관련 페이지
- `src/app/error-pages` : 에러 페이지
- `src/app/shared` : 네비게이션, 사이드바, 푸터 등 공통 레이아웃

## 설치 및 실행

```bash
npm install
npm start
```

## 주요 사용 라이브러리

- React 16.x
- react-router-dom
- react-bootstrap, bootstrap
- chart.js, react-chartjs-2
- i18next, react-i18next
- @mdi/font, flag-icon-css 등
