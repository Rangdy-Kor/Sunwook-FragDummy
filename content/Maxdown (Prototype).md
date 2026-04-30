---
publish: true
---

# Maxdown (Prototype)

---

## 문법

---

### 규칙

---

1. GFM → Maxdown으로의 단방향 호환성의 유지
2. Maxdown → GFM으로의 변환 시 작성자의 의도를 파편적으로나마 전달, 이는 문서의 깨짐이 아닌 기능적 축소로 정의
3. 문서에서 기계가 읽는 곳 (프론트매터)와 사람이 읽는 곳 (본문)을 철저히 구분
4. 본문에서의 HTML의 사용은 최대한 기피, 마크업 블록은 예외
5. 언제나 GFM 슈퍼셋으로 남아야 하고, 언제나 .md 확장자를 사용
6. 텍스트를 감싸는 토큰 문법에서 서로 다른 기호의 연속된 사용은 기피

### 기본 구조

---

- `<br>` → 줄바꿈 문자 1번
- `<p>` → 줄바꿈 문자 2번 (빈 줄 1개)
- 이스케이프 → 역슬래시 (`\`) 사용, 글자 단위가 아닌 단어 단위로 적용
- 리터럴 역슬래시 → 역슬래시 2번 (`\\`)
- Maxdown 주석 → 물음표 2번 + 텍스트와의 공백 (`?? Text ??`)
- 최소 의미 단위 → 단락 (`<p>`)
- 최소 구조 단위 → 헤딩
- 최소 저장 단위 → 페이지 (.md 파일의 추상화)

### 형태

---

- Bold → `**Text**` | `__Text__`
- Italic → `*Text*` | `_Text_`
- Strikethrough → `~~Text~~`
- Underline → `~Text~`
  - 물결표는 Typora 등에서 검증된 토큰 조합
- Superscript → `^^Text^^`
  - LaTeX 없는 위첨자의 필요
- Subscript → `,,Text,,`
  - 연속 쉼표는 자연어에서 사실상 사용되지 않는 토큰 조합\`

### 색상

---

- Colored → `++ColorCode | Content++`
  - `ColorCode`에는 HexCode, 16색 HexCode, RGBA HexCode, CSS Color, CSS Var, 사용 가능
  - `++ColorCode1, ColorCode2 | Content` 형식으로 라이트 테마와 다크 테마 색상 분리 가능
- Highlight → `==ColorCode | Content==`
  - `ColorCode`에는 HexCode, 16색 HexCode, RGBA HexCode, CSS Color, CSS Var, 사용 가능
  - `++ColorCode1, ColorCode2 | Content` 형식으로 라이트 테마와 다크 테마 색상 분리 가능

### 크기

---

- Sized → `%%Value(unit) | Content%%`
  - `(unit)`에는 rem,  px, % 사용 가능
  - %는 횟수 기반 정규 표현식으로 문법 토큰과 충분히 구별 가능
  - %는 전체 문서 너비 대비 크기
  - 단위 생략 시 rem 기본 사용

### 리스트

---

- Bullet List → `- Content`
  - 중첩 리스트 / 리스트 내부 줄바꿈은 들여쓰기 (TAB 문자, Space 문자)로 사용 가능
- Ordered List → `(OrderMark). Content`
  - 중첩 리스트 / 리스트 내부 줄바꿈은 들여쓰기 (TAB 문자, Space 문자)로 사용 가능
  - `(OrderMark)`에는 아라비아 숫자, 알파벳 대/소문자, 로마 숫자 대/소문자를 사용 가능
  - 렌더링된 글머리는 자동으로 순번이 열거됨
  - 리스트 중간에서 순번 교체를 위해서는 `(OrderMark).#(ChangeOrderMark)`를 입력
