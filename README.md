# GitHub Portfolio — 3-column Project Grid

참고 이미지처럼 프로젝트 영역을 다음 구조로 변경한 버전입니다.

- 3열 프로젝트 그리드
- 큰 정사각형 프로젝트 썸네일
- 이미지 바로 아래 기술 스택
- 그 아래 굵은 프로젝트 제목
- 태블릿 2열 / 모바일 1열

## 파일 구조

```text
jmoonxai.github.io/
├── index.html
├── css/
│   └── style.css
└── assets/
    ├── images/
    └── resume.pdf
```

## 프로젝트 이미지 넣는 방법

현재 프로젝트 썸네일 부분:

```html
<a href="#" class="project-thumb placeholder-thumb">
  <span>ADD PROJECT IMAGE</span>
</a>
```

이미지를 넣을 때:

```html
<a href="./projects/fire-response.html" class="project-thumb">
  <img src="./assets/images/fire-response.jpg" alt="Multi-Robot Fire Response System">
</a>
```

`assets/images/` 폴더에 실제 이미지 파일을 업로드하면 됩니다.

## 추천 이미지 파일명

```text
assets/images/fire-response.jpg
assets/images/crime-scene-robot.jpg
assets/images/ocr.jpg
assets/images/disaster-tweets.jpg
assets/images/smart-farm.jpg
```
