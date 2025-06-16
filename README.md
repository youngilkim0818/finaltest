# KMU 도서관 시스템 (KMU Library Management System)

계명대학교 도서관 관리 시스템입니다. Django 웹 프레임워크로 구축되었습니다.

## 주요 기능

- 📚 **도서 검색**: 제목, 저자별 도서 검색
- 📖 **도서 대출**: 온라인 도서 대출 시스템
- 📝 **대출 이력**: 개인 대출 내역 조회 및 통계
- 📋 **예약 시스템**: 대출 중인 도서 예약 기능
- ⭐ **인기 도서**: 대출 횟수 기반 인기 도서 조회
- 📢 **공지사항**: 도서관 공지사항 확인
- 🕐 **운영시간**: 도서관 운영시간 안내

## 기술 스택

- **Backend**: Django 5.2.3
- **Database**: SQLite
- **Frontend**: HTML, CSS, Bootstrap 5
- **Icons**: Font Awesome 6

## 설치 및 실행

1. 리포지토리 클론
```bash
git clone https://github.com/youngilkim0818/finaltest.git
cd finaltest
```

2. 가상환경 생성 및 활성화
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. 의존성 설치
```bash
pip install django
```

4. 데이터베이스 마이그레이션
```bash
python manage.py migrate
```

5. 서버 실행
```bash
python manage.py runserver
```

6. 브라우저에서 `http://127.0.0.1:8000` 접속

## 프로젝트 구조

```
kmu-lms-main/
├── accounts/           # 사용자 계정 관리
├── library/           # 도서관 주요 기능
├── library_info/      # 도서관 정보
├── myadmin/          # 관리자 기능
├── notices/          # 공지사항
├── templates/        # HTML 템플릿
├── kmu_lms_project/ # 프로젝트 설정
├── manage.py        # Django 관리 스크립트
└── README.md        # 프로젝트 설명
```

## 주요 수정사항

- ✅ 대출 이력 통계 오류 수정 (반납 완료 개수가 올바르게 증가)
- ✅ 네비게이션 메뉴에 예약 내역 추가
- ✅ 로그인한 사용자를 위한 개선된 UI

## 기여자

- youngilkim0818

## 라이선스

이 프로젝트는 교육 목적으로 제작되었습니다. 