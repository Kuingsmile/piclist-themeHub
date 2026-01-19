# PicList 主题

本主题适用于 [PicList](https://github.com/Kuingsmile/PicList) 应用。

PicList 是一款开源的图片管理软件，支持本地和云端图片的浏览与管理。

## 安装方法

下载主题文件后，将其放置在 PicList 应用配置目录下的 `themes` 文件夹中。然后在应用的设置中选择该主题即可。

![](https://github.com/user-attachments/assets/94db6aff-5614-4b7d-a2a5-1a949b1f5a4d)

## 主题代码贡献

参考`default.css`文件的结构，您可以根据自己的喜好修改颜色变量来创建自定义主题，测试后将代码提交至本仓库，可分享给更多用户使用。

以下是一个示例主题代码：

```css
/* 主题名 */

/* 浅色 */
:root,
.light,
[data-theme='light'] {
  --background-image: url("http://xxx.com/img.png") !important;
  --background-image-opacity: 0.7 !important;
  --background-blur: 5px !important;
  --color-text-primary: #1d1d1f !important;
  --color-text-secondary: #6e6e73 !important;
  --color-text-tertiary: #86868b !important;
  --color-background-primary: #ffffff !important;
  --color-background-secondary: #f5f5f7 !important;
  --color-background-tertiary: #fbfbfd !important;
}

/* 深色 */
:root.dark,
.dark,
[data-theme='dark'] {
  --background-image: url("http://xxx.com/img.png") !important;
  --background-image-opacity: 0.7 !important;
  --background-blur: 5px !important;
  --color-text-primary: #f5f5f7 !important;
  --color-text-secondary: #a1a1a6 !important;
  --color-text-tertiary: #86868b !important;
  --color-background-primary: #000000 !important;
  --color-background-secondary: #1c1c1e !important;
  --color-background-tertiary: #2c2c2e !important;
}
```