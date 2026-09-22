# chobo-project

동아리 사이트. Flask 기반.

## Stack
- Python 3 / Flask
- Jinja2 템플릿 (templates/)
- 정적 파일 (static/css, static/js)

## 구조
```
app.py              # Flask 엔트리포인트
templates/
  base.html          # 공통 레이아웃
  index.html          # 홈 페이지
static/
  css/style.css
  js/
```

## 실행
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

## 컨벤션
- 새 페이지는 templates/에 base.html 상속해서 추가
- 라우트는 app.py에 추가 (규모 커지면 blueprints로 분리 고려)
- 커밋 메시지는 한글/영어 무관, 간결하게

## Git
- origin: https://github.com/leeseojoon5793/chobo-project.git
- main 브랜치 기준 작업
