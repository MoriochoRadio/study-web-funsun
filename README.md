# FUN-SUN — 첫 HTML 토이 프로젝트 "THE SUN" (2020)

> 2020년 1월, HTML 을 막 배우자마자 만든 토이 웹사이트. "THE SUN" 이라는 인물의 인생을 단계별 페이지 (Birth → Elementary → Middle → High school) 로 구성한 첫 스토리텔링형 웹 시도입니다.

---

## 📚 학습 컨텍스트

- **시기:** 2020년 1월 (`Web1` 와 동시기)
- **사용 기술:** HTML 만 (CSS·JS 없음)
- **컨셉:** 가상의 인물 (혹은 별명) "THE SUN" 의 인생 페이지
- **학습 포인트:** 페이지 간 링크 (`<a href>`) 로 작은 "사이트" 를 구성하는 첫 경험

---

## 🧭 파일 구조

| 파일 | 내용 |
|---|---|
| `SUN.html` | **인덱스 페이지** — 4단계로 분기되는 메뉴 |
| `Birth.html` | 출생 — 본문은 `<h1>SECRET</h1>` 만 |
| `Elementary.html` | 초등 시기 — `<h1>SECRET</h1>` 만 |
| `middle.html` | 중등 시기 — `<h1>SECRET</h1>` 만 |
| `high school.html` | 고등 시기 — **유일하게 서사적 본문이 채워진 페이지** |
| `sun.jpg` | 메인 이미지 |

---

## 💡 흥미

`SUN.html` 의 인덱스 구조:
```html
<h1><a href="SUN.html"><strong>THE SUN</strong></a></h1>
<img src="sun.jpg" width="200$">
<ol>
  <li><a href="Birth.html">The Birth</a></li>
  <li><a href="Elementary.html">The Elementary</a></li>
  <li><a href="middle.html">The Middle</a></li>
  <li><a href="high school.html">The High school</a></li>
</ol>
```

대부분의 페이지는 `<h1>SECRET</h1>` 만 적혀 있는데, **`high school.html` 한 페이지에만 본문이 있습니다**:

```html
<h1>역사의 시작, 그의 등장.</h1>

<h2><strong>그</strong></h2>를 처음 보는 순간.<br>
강렬한 빛이 쏟아졌다.<br>
그가 자리에 앉자, 공기가 끓어오르기 시작했다.<br>
```

코드 학습보다 *"내가 만든 페이지로 이야기를 한다"* 다섯 페이지 중 한 페이지만 완성된 미완의 토이 프로젝트.



---


---

## 🗂️ 같은 시기의 학습 레포

- [`Web1`](https://github.com/MoriochoRadio/Web1) — 같은 시기의 HTML/CSS/JS 기초 학습

---

*Author: [MoriochoRadio](https://github.com/MoriochoRadio) (KimTaeKyoung) · 의료IT공학 전공*
