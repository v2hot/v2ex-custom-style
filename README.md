# v2ex-custom-style ![GitHub release (latest by date)](https://img.shields.io/github/v/release/v2hot/v2ex-custom-style?style=flat-square)

V2EX 自定义样式 🌈

## Usage

把下面 CSS 代码，放到 [**v2ex > 设置 > 自定义 CSS**](https://www.v2ex.com/settings) 或 [**stylish**](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe) 里面即可。

![v2ex-settings](assets/v2ex-settings.png)
![stylish](assets/stylish.png)

⚠️ 注意：下面 URL 的 `VERSION` 要改成最新或指定的[版本](https://github.com/v2hot/v2ex-custom-style/releases)。![GitHub release (latest by date)](https://img.shields.io/github/v/release/v2hot/v2ex-custom-style?style=flat-square)

例如：`latest`, `1.0.0`, `1.0.1` 等。

### 按需加载 CSS 文件

#### 节点显示增强

```css
@import "https://cdn.jsdelivr.net/gh/v2hot/v2ex-custom-style@VERSION/enhance-node-name.css";
```

#### 隐藏头像

```css
@import "https://cdn.jsdelivr.net/gh/v2hot/v2ex-custom-style@VERSION/hide-profile-photo.css";
```

#### 导航栏固定在顶端

```css
@import "https://cdn.jsdelivr.net/gh/v2hot/v2ex-custom-style@VERSION/sticky-header.css";
```

#### 搜索框 like `command` + `k`

```css
@import "https://cdn.jsdelivr.net/gh/v2hot/v2ex-custom-style@VERSION/search.css";
```

#### 隐藏广告

```css
@import "https://cdn.jsdelivr.net/gh/v2hot/v2ex-custom-style@VERSION/no-ads.css";
```

#### 极简风格

```css
@import "https://cdn.jsdelivr.net/gh/v2hot/v2ex-custom-style@VERSION/minimalist.css";
```

### 加载全部

加载上面全部 CSS

```css
@import "https://cdn.jsdelivr.net/gh/v2hot/v2ex-custom-style@VERSION/style.css";
```

### 其他

#### 自定义隐藏

请 fork 代码，按自己需要修改。

或把 CSS 代码直接写在 **v2ex > 设置 > 自定义 CSS** 或 **stylish** 里面。

```css
@import "https://cdn.jsdelivr.net/gh/v2hot/v2ex-custom-style@VERSION/hide-custom.css";
```

## Related

- [v2ex 知乎主题](https://github.com/viewweiwu/v2ex-zhihu-theme) [https://www.v2ex.com/t/822425](https://www.v2ex.com/t/822425)
- [v2ex qiita theme (绿色主题)](https://github.com/viewweiwu/v2ex-qiita-theme) [https://www.v2ex.com/t/864473](https://www.v2ex.com/t/864473)
- [V2EX 仿微信风格 CSS](https://github.com/CrazyMelody/v2ex_style) [https://www.v2ex.com/t/851399](https://www.v2ex.com/t/851399)

## >\_

[![Pipecraft](https://img.shields.io/badge/site-pipecraft-brightgreen)](https://www.pipecraft.net)
[![DTO](https://img.shields.io/badge/site-DTO-brightgreen)](https://dto.pipecraft.net)
[![BestXTools](https://img.shields.io/badge/site-bestxtools-brightgreen)](https://www.bestxtools.com)
