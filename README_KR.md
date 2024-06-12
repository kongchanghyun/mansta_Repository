
# Mansta Club

이 프로젝트는 Mansta Club 온라인 쇼핑몰을 위한 Django 프로젝트입니다.

## 설치 방법

1. 저장소를 클론합니다.
   ```bash
   git clone <저장소-URL>
   cd myshop
   ```

2. 의존성을 설치합니다.
   ```bash
   pip install django
   ```

3. 마이그레이션을 적용합니다.
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. 관리자 계정을 생성합니다.
   ```bash
   python manage.py createsuperuser
   ```

5. 개발 서버를 실행합니다.
   ```bash
   python manage.py runserver
   ```

## 사용 방법

- `/admin/` URL로 접속하여 관리자 패널에 로그인합니다.
- 관리자 패널에서 제품을 추가하고 관리할 수 있습니다.
- 메인 페이지에는 쇼핑몰의 제품들이 표시됩니다.

## 디렉토리 구조

- `myshop/` - Django 프로젝트 설정
- `shop/` - 제품 관리를 위한 애플리케이션
- `templates/` - HTML 템플릿
- `static/` - 정적 파일 (CSS, JS, 이미지)
- `media/` - 업로드된 미디어 파일
