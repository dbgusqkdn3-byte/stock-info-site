# CLAUDE.md

## HTML 파일 생성 규칙

새 HTML 파일을 만들 때는 반드시 `</head>` 앞에 아래 태그를 포함할 것:

```html
<link rel="stylesheet" href="/mobile.css">
```

- 모바일 반응형 스타일은 `mobile.css` 하나로 통일한다.
- 개별 HTML 파일에 모바일용 미디어 쿼리를 중복 삽입하지 않는다.
