## Day 1 (2025-08-17)
- Git 설치 및 GitHub 계정 만들기
- GitHub 저장소(repository) 생성
- 내 컴퓨터와 GitHub 저장소 연결 (git clone, git remote 설정)
- VS Code 설치 및 기본 사용법 익히기
- Git 기본 명령어 실습: git status, git add, git commit, git push

## Day 2 (2025-08-18)
- HTML 태그 실습: h1~h2, ul/li, br, strong, em, hr
- CSS 실습: padding, margin, border-radius
- 내 소개 페이지 완성 (index.html + style.css)
- GitHub commit & push 경험

## Day 3 (2025-08-19)
- HTML 레이아웃 태그 학습: header, nav, main, section, article, aside, footer
- CSS 선택자 학습: 태그, 클래스(.), 아이디(#), 전체(*)
- CSS 박스 모델 이해: margin, border, padding, content
- 간단한 블로그 레이아웃 페이지 완성

# Day 4 - 2025.08.20

## 📚 오늘 공부한 내용
- HTML 여러 페이지 만들기 (`index.html`, `about.html`)
- CSS 파일 분리해서 적용 (`style.css`)
- `<link>` 태그로 CSS 연결하는 방법

---

## 🧠 오늘 배운 개념 정리
- `<link rel="stylesheet" href="style.css">` : HTML에 외부 CSS 파일을 연결
- 모든 HTML 파일에서 같은 `style.css`를 불러올 수 있음 → 유지보수 편리
- 파일 이름 규칙: 영어 소문자, 띄어쓰기 X, 확장자 정확히

---

## 💻 코드 예시
```html
<!-- index.html -->

-<img src="images/cat.jpg" alt="고양이" width="200">
-<ul>
        <li>딸기</li>
        <li>수박</li>
        <li>망고</li>
-</ul>
-<a href="about.html">홈</a>

<!-- anout.html -->

-<ol>
        <li>첫 번째</li>
        <h3>코딩 공부</h3>
        <li>두 번째</li>
        <h3>국어 공부</h3>
        <li>세 번째</li>
        <h3>잠 잘자기</h3>
 </ol>

```

## ❗ 어려웠던 점 / 헷갈렸던 점

- `<ul>` 과 `<ol>` 차이가 헷갈렸음
- HTML에 외부 CSS 파일 연결하는 것

## ✨ 오늘의 한 줄 회고

- 다음에는 index랑 about 따로따로 css 파일 연결해보기!

# Day 5 - 2025.08.21

## 📚 오늘 공부한 내용
- 오늘 배운 주제:
  - CSS margin / padding 차이
- 실습한 것:
  - index.html과 about.html 디자인 다르게 적용


---

## 🧠 오늘 배운 개념 정리
- `margin` : 요소의 **바깥 여백** (다른 요소와의 간격)
- `padding` : 요소의 **안쪽 여백** (콘텐츠와 테두리 사이 공간)
- `display: flex;` : 요소들을 가로/세로로 배치할 수 있는 레이아웃 시스템
- 

---

## 💻 코드 예시
```html
 <link rel="stylesheet" href="index.css">
 <link rel="stylesheet" href="about.css">

section {
  flex: 3;
  margin-right: 20px;
}
```

## ❗ 어려웠던 점 / 헷갈렸던 점

- `margin`과 `padding` 차이가 아직 헷갈림 (겹쳐지는 경우를 더 연습 필요)

- `flexbox` 속성이 많아서 한 번에 다 외우기 어려움

## ✨ 오늘의 한 줄 회고

- CSS는 코드 몇 줄만 바꿔도 화면이 확 달라지는 게 신기하다 다음에는 더 다양한 색으로 꾸며봐야겠다.

# Day 6 - 2025.08.22
## 📚 오늘 공부한 내용

오늘 배운 주제:

HTML `<div>`와 클래스 사용법

CSS로 카드 UI 디자인하기 (`.card` 스타일링)

프로필 사진 원형 만들기 (`border-radius: 50%`)

`margin` / `padding`의 차이 복습

실습한 것:

`about.html`, `about.css` 파일 작성

프로필 카드 만들기

## 🧠 오늘 배운 개념 정리

`<div>` : 여러 요소들을 묶는 컨테이너 역할. class 속성을 주어 CSS와 연결 가능.

`<img src="주소" alt="설명">` : 이미지를 불러오는 태그. alt는 이미지가 안 뜰 때 보여줄 글.

`margin` : 바깥 여백, 다른 요소와의 거리.

`padding` : 안쪽 여백, 박스 내부 내용과 테두리 사이의 거리.

`border-radius: 50%` : 정사각형 이미지를 원형으로 자를 수 있음.

`box-shadow` : 박스에 그림자 효과를 줘서 입체감을 만듦.

## 💻 코드 예시
```
<div class="card">
  <img src="https://via.placeholder.com/150" alt="내 사진">
  <h2>홍길동</h2>
  <p>웹 개발자가 되기 위해 공부 중입니다!</p>
</div>

.card {
  width: 300px;
  padding: 20px;
  margin: 50px auto;
  border: 1px solid #ddd;
  border-radius: 10px;
  text-align: center;
  box-sizing: border-box;
  background: #fff;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.card img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
}
```
## ❗ 어려웠던 점 / 헷갈렸던 점

CSS 파일이 적용이 안 될 때 원인이 뭔지 찾는 게 어려웠음. (링크 경로 문제, 오타 확인 필요)

`margin`/`padding` 차이를 코드로 직접 비교하면서 조금 더 익혀야겠다고 느낌.

## ✨ 오늘의 한 줄 회고

CSS로 꾸민다는게 무슨 느낌인지 알듯말듯

# Day 7 - 2025.08.25
## 📚 오늘 공부한 내용

- 오늘 배운 주제:

- 버튼(`<button>`, `<a>`) 추가 방법

- `<a>` 태그 꾸미기 (링크 스타일링)

- CSS에서 `hover` 효과 이해하기

- 실습한 것:

- `index`, `about` 페이지에 버튼 추가

- 버튼 `hover` 효과 실습 (색, 크기 변화)

- `<a>` 태그 밑줄 제거, 색상 변경

## 🧠 오늘 배운 개념 정리

- `<a>`: 링크를 만드는 태그 (다른 페이지나 외부 사이트로 이동 가능)

- `text-decoration: none;` → `<a>` 태그 밑줄 제거

- `.button` 클래스: CSS로 링크를 버튼처럼 꾸밀 수 있음

- `hover:` 마우스를 올렸을 때 변화하는 CSS 효과

- `transform: scale(1.05);` → 크기를 1.05배 크게 만들어 눌러보고 싶게 함

## 💻 코드 예시
```
<a href="about.html" class="button">About Me</a>

.button {
  display: inline-block;
  padding: 12px 24px;
  background: #3498db;
  color: #fff;
  border-radius: 5px;
  text-decoration: none;
  transition: all 0.3s ease;
}

.button:hover {
  background: #2980b9;
  transform: scale(1.05);
}
```

## ❗ 어려웠던 점 / 헷갈렸던 점

- 버튼을 `<button>`으로 쓸지 `<a>` 태그로 꾸밀지 헷갈림

- `hover` 효과가 적용되지 않을 때, CSS 파일 연결 여부를 확인해야 한다는 걸 알게 됨

## ✨ 오늘의 한 줄 회고

- 오류가 너무 많이나서 살짝 지쳤다

