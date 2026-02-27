# 📦 USDZ Hosting — Updated

<p align="center">
  <img src="https://img.shields.io/badge/GitHub Pages-C9E4FF?style=for-the-badge&logo=github&logoColor=black"/>
  <img src="https://img.shields.io/badge/AR Quick Look-D4F1C0?style=for-the-badge&logo=apple&logoColor=black"/>
  <img src="https://img.shields.io/badge/USDZ-FFE4A0?style=for-the-badge&logoColor=black"/>
</p>

<br/>

> FORK 프로젝트의 AR 기능 구현을 위해 `.usdz` 파일을 호스팅하는 레포지토리입니다.

<br/>

## 📌 개요

[FORK](https://github.com/FORK-FE-BE) 프로젝트에서 음식 AR 미리보기 기능을 구현할 때, iOS AR Quick Look에서 3D 모델을 불러오기 위해 `.usdz` 파일의 **공개 URL**이 필요했습니다.

GitHub Pages를 통해 `.usdz` 파일을 호스팅하여 FORK 서비스의 AR 뷰어와 연결했습니다.

<br/>

## 🔗 연관 프로젝트

| 프로젝트 | 설명 |
|:---:|:---:|
| [FORK](https://github.com/FORK-FE-BE) | AI 추천 배달 서비스 (AR 음식 미리보기 기능 포함) |

<br/>

## 🛠 사용 방식

1. `.usdz` 3D 모델 파일을 이 레포지토리에 업로드
2. GitHub Pages를 통해 파일의 공개 URL 생성
3. FORK 프로젝트에서 해당 URL로 AR Quick Look 연결

```html
<!-- iOS Safari에서 AR Quick Look 연동 예시 -->
<a href="https://ye-eun-min201.github.io/usdz-hosting/모델명.usdz"
   rel="ar">
  <img src="썸네일.png" />
</a>
```

<br/>

## 📁 파일 구조

```
usdz-hosting/
├── *.usdz        # AR 3D 모델 파일들
└── README.md
```

<br/>

## 📎 참고

- `.usdz`는 Apple과 Pixar가 공동 개발한 AR용 3D 파일 포맷입니다.
- iOS 12 이상의 Safari에서 AR Quick Look으로 바로 실행됩니다.
