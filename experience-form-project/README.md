# 체험단 제출 폼 프로젝트

GR-EAT 체험단 제출을 위한 웹 폼 프로젝트입니다.

## 프로젝트 개요

- **목적**: 체험단 참가자들의 정보를 수집하는 웹 폼
- **캠페인**: 테팔 라이트믹스 체험단
- **기능**: 이름, 휴대폰 번호, 인스타그램 URL 입력 및 제출

## 파일 구조

```
experience-form-project/
├── index.html          # 메인 폼 페이지
└── README.md          # 프로젝트 설명서
```

## 주요 기능

- **반응형 디자인**: 모바일 친화적인 UI
- **다크 테마**: 모던한 네온 그린 컬러 스킴
- **폼 검증**: 휴대폰 번호 및 인스타그램 URL 형식 검증
- **Google Apps Script 연동**: 제출된 데이터를 스프레드시트에 저장
- **로딩 상태 표시**: 제출 중 로딩 오버레이

## 사용 방법

1. `index.html` 파일을 웹 브라우저에서 열기
2. 필수 정보 입력:
   - 이름
   - 휴대폰 번호 (하이픈 없이 숫자만)
   - 인스타그램 URL
3. "제출하기" 버튼 클릭

## 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Google Apps Script
- **데이터 저장**: Google Sheets

## 설정 정보

- **캠페인명**: 테팔_라이트믹스
- **웹앱 URL**: Google Apps Script 배포 URL 사용
- **CORS 처리**: URL-encoded 폼 데이터로 전송

## 브라우저 지원

- Chrome, Firefox, Safari, Edge 등 모던 브라우저
- 모바일 브라우저 지원
