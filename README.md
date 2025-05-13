# WebAR 演示项目

这是一个使用 AR.js 和 A-Frame 框架构建的简单WebAR演示项目。

## 功能特点

- 使用网页浏览器即可体验AR
- 基于图像识别的AR标记跟踪
- 3D模型展示

## 使用方法

1. 将项目部署到Web服务器上（本地开发可以使用 Live Server 等工具）
2. 使用支持WebAR的移动设备浏览器访问页面
3. 允许相机权限
4. 将相机对准"Hiro"标记（[点击下载Hiro标记](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/HIRO.jpg)）
5. 你将看到一个红色立方体悬浮在标记上方

## 技术栈

- AR.js
- A-Frame
- HTML5

## 注意事项

- 需要使用HTTPS协议（除了localhost）
- 需要允许相机权限
- 建议使用最新版本的Chrome或Firefox浏览器
- 确保环境光线充足，标记图案清晰可见

## 自定义开发

要添加自己的3D模型或修改AR效果，可以：

1. 修改 `<a-marker>` 标签内的内容来更改AR显示的3D对象
2. 使用自定义的标记图片（需要生成对应的pattern文件）
3. 添加更多的交互效果和动画

## 问题排查

如果遇到问题：

1. 确认使用HTTPS协议访问
2. 检查是否允许了相机权限
3. 确保环境光线充足
4. 保持标记图案完整、清晰可见 