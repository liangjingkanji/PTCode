本字体为`PT Mono`增添连字(Ligature)特性

## 安装

1. [点击下载](https://codeload.github.com/liangjingkanji/PTCode/zip/refs/heads/master)
2. 网页字体引用

```css
@font-face{
    font-family: 'PT Code';
    src: local('PT Code'),
         url('https://raw.githubusercontent.com/liangjingkanji/PTCode/master/font/PTCode-Regular.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
}
* {
    -webkit-font-feature-settings: "liga" on, "calt" on;
    -webkit-font-smoothing: subpixel-antialiased;
    text-rendering: optimizeLegibility;
    font-family: 'PT Code' !important;
}
```



## 预览

代码渲染

<img src="https://i.imgur.com/scaWsx5.png" width="600px" /> 



连字特性

<img src="https://i.imgur.com/o4thUkz.png" width="450px" /> 



文章

![image-20210312130233258](https://i.imgur.com/anUL0N6.png)



截图来自于[DrakeTyporaTheme](https://github.com/liangjingkanji/DrakeTyporaTheme)

## LICENSE

```
Copyright (C) 2018 Drake, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

