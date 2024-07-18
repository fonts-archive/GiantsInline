# 자이언츠체 Inline

[배포처 바로가기](https://www.giantsclub.com/html/?pcode=1007)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Giants Inline`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GiantsInline/GiantsInline.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GiantsInline/GiantsInline.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Giants Inline';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GiantsInline/GiantsInline.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GiantsInline/GiantsInline.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GiantsInline/GiantsInline.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GiantsInline/GiantsInline.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GiantsInline/subsets/GiantsInline-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GiantsInline/subsets/GiantsInline-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Giants Inline", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
자이언츠체 글꼴 사용 조건 및 안내 
자이언츠체의 지적재산권은 모두 (주)롯데자이언츠에 있습니다. 
자이언츠체는 무료로 사용할 수 있으며, 본 사용규정 안내 전문을 포함하여 재배포하실 수 있습니다. 
정확한 사용 조건은 아래 라이선스 전문을 참고하시기 바랍니다 
 
상세 사용규정 
사용 제한 및 조건 
1. 자이언츠체는 인쇄나 출판, 영상, 웹, 모바일 등에 자유롭게 사용할 수 있습니다. 
2. 자이언츠체를 수정하거나 다른 포맷으로 변형하여 사용하는 것은 엄격하게 금지됩니다. 
3. 자이언츠체는 폰트 소프트웨어 또는 개별 구성요소인 폰트 자체로 유료로 판매할 수 없습니다. 
4. 자이언츠체는 전체나 부분 여부에 상관 없이 저작권자 안내와 본 라이선스 규정 내용을 포함하는 경우에는 다른 소프트웨어와 함께 묶이거나 재배포가 가능합니다. 
5. 자이언츠가 사용된 인쇄물, 광고물(온라인 포함) 이미지 등은 롯데자이언츠가 홍보 목적을 위해 활용할 수 있습니다. 
이를 원치 않는 사용자는 언제든지 당사 고객센터로 요청 부탁드립니다. 
6. 본 라이선스는 상기 조건 중 일부라도 부합되지 않으면 무효가 될 수 있습니다. 
7. 롯데자이언츠는 자이언츠체의 사용 또는 기타 자이언츠체의 취급과 관련하여 발생하는 어떠한 책임도 가지지 않습니다.
```
