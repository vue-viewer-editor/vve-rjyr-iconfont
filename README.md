VVE RJYR ICONFONT

> vve rjyr 字体图标

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

## 特性
- webpack4
- babel7
- dart-sass
- ali iconfont

## 目前有的字体
```css
$icf-css-prefix: "vve-rjyr-icon";
.#{$icf-css-prefix}-setting2:before { content: "\e60c"; }
.#{$icf-css-prefix}-status:before { content: "\e60b"; }
.#{$icf-css-prefix}-setting:before { content: "\e60a"; }
.#{$icf-css-prefix}-status1:before { content: "\e609"; }
.#{$icf-css-prefix}-app:before { content: "\e608"; }
.#{$icf-css-prefix}-warning:before { content: "\e607"; }
.#{$icf-css-prefix}-app1:before { content: "\e606"; }
.#{$icf-css-prefix}-warning1:before { content: "\e605"; }
```

### npm安装使用

```bash
npm install vve-rjyr-iconfont
```

引入样式
```bash
import 'vve-rjyr-iconfont/dist/vve-rjyr-iconfont.css'
```

如果你的项目支持sass，你可以直接引用
```bash
import 'vve-rjyr-iconfont/src/index.scss'
```

### CDN安装使用

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/vve-rjyr-iconfont@1.0.1/dist/vve-rjyr-iconfont.css">
```

## 开发

- 安装依赖

```bash
npm install
```

- 开发

```bash
npm run dev
```

- 打包

```bash
npm run build
```

- 发布

```bash
npm run release
git push --follow-tags origin master && npm publish
```
