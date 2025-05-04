# 솔뫼 김대건체

[배포처 바로가기](http://www.kimdaegeon.com/design/node/?menu=font)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Solmoe KimDaeGeon`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Solmoe KimDaeGeon';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon-Light.woff2') format('woff2'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon-Light.woff') format('woff'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon-Light.otf') format('opentype'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'Solmoe KimDaeGeon';
  font-weight: 500;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon-Medium.woff2') format('woff2'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon-Medium.woff') format('woff'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon-Medium.otf') format('opentype'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SolmoeKimDaeGeon/SolmoeKimDaeGeon-Medium.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Solmoe KimDaeGeon", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
솔뫼 김대건 글꼴은 자유롭게 수정·변경하여 영리적·비영리적 목적으로 개인 및 기업 사용자가 모두 사용하실 수 있으나, 다만, 글꼴 폰트 파일(otf/ttf)자체를 유상으로 판매하는 것은 금지하고 있으니 유의 부탁드립니다.
```
