# 全自动网页剥壳机 (URL to Markdown)

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-4285F4?logo=googlechrome&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-brightgreen.svg)

> 一个轻量级浏览器插件，一键提取网页正文并转换为干净纯粹的 Markdown 格式。

## ✨ 核心特性

- **智能提取**：基于 Readability 算法，识别网页文章的主体内容（标题、正文、图片等）。
- **纯净 Markdown**：将复网页 DOM 结构转换为标准的 Markdown 语法。
- **无感剔除**：自动过滤掉广告、弹窗、导航栏、底部版权声明等无关内容。
- **轻量安全**：基于 Manifest V3 规范开发，仅请求必要的 `activeTab` 和 `scripting` 权限，完全在本地处理，保护您的隐私。

## 🚀 安装指南

由于当前处于开发阶段/未上架扩展商店，请通过“加载已解压的扩展程序”方式进行安装：

1. 下载或克隆本仓库代码到本地。
2. 打开 Chrome 或 Edge 浏览器，在地址栏输入：
   - Chrome: `chrome://extensions/`
   - Edge: `edge://extensions/`
3. 在页面右上角（或左下角）打开 **“开发者模式”** (Developer mode)。
4. 点击左上角的 **“加载已解压的扩展程序”** (Load unpacked) 按钮。
5. 选择本项目的文件夹（即包含 `manifest.json` 的目录）。
6. 安装成功！您可以在浏览器右上角的扩展栏中看到它的图标（建议将其固定在工具栏以方便使用）。

## 💡 使用方法

1. 在浏览器中打开您想要提取内容的文章或网页页面。
2. 点击浏览器右上角的 **全自动网页剥壳机** 插件图标。
3. 在弹出的面板中，点击 **“提取并复制 Markdown”** 按钮。
4. 插件会自动进行提取。提取成功后，Markdown 内容将自动复制到您的剪贴板，同时会在面板底部的文本框中展示。
5. 打开您的编辑器或软件，直接 `Ctrl+V` (或 `Cmd+V`) 粘贴即可！

## 🛠️ 技术栈

- **Manifest V3**: 最新一代 Chrome 扩展标准。
- **Readability**: Mozilla 的网页正文提取引擎。
- **HTML/CSS/JS**: 无庞大的前端框架，保证加载和运行速度。

## 📄 许可证 (License)

本项目基于 [MIT](LICENSE) 协议开源。