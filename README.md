# JavAssistant Ultimate | Jav 助手终极版

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-24.0-blue.svg)]()

一个功能强大的浏览器扩展，专为影视番号自动识别、磁力链接处理及 BBS 论坛优化而生。
A powerful browser extension designed for automatic AV code identification, magnet link processing, and BBS forum optimization.

---

## ✨ 核心功能 | Features

### 1. 智能识别 (Smart Identification)
* **全格式支持**：精准识别标准番号（如 `MIDE-123`）及模糊格式（如 `sinn023`, `stars 968`）。
* **FC2 专项优化**：自动补全并识别 `FC2-PPV` 变体，支持带空格或不规范写法。
* **BBS 标题穿透**：唯一支持在论坛列表页标题中直接高亮番号，无需进帖即可预览。

### 2. 交互体验 (Interactive Experience)
* **悬浮预览窗**：点击普通番号弹出内嵌 JavBus 详情页，支持**全边框拖拽移动**。
* **自定义缩放**：右下角拉伸即可调整窗口大小，并自动记忆位置与尺寸。
* **FC2 快速直达**：点击 FC2 番号直接跳转至 MissAV 搜索，解决内嵌限制。

### 3. 磁力工具 (Magnet Integration)
* **一键复制**：高亮 Magnet 链接及 40 位 Hash 识别码（紫色标识）。
* **自动补全**：点击纯识别码时，自动补全为 `magnet:?xt=urn:btih:` 格式后存入剪贴板。
* **视觉反馈**：内置轻量级“复制成功”提示。

---

## 🚀 安装步骤 | Installation

1. **下载项目**：点击右上角 `Code` -> `Download ZIP` 并解压到本地。
2. **加载扩展**：
   - 打开 Chrome/Edge 浏览器，访问 `chrome://extensions/`。
   - 开启右上角的 **“开发者模式” (Developer Mode)**。
   - 点击 **“加载已解压的扩展程序” (Load unpacked)**。
   - 选择解压后的文件夹。
3. **固定图标**：点击浏览器拼图图标，将 JavAssistant 固定在任务栏。

---

## 🛠 技术实现 | Technical Details

* **双路匹配引擎**：基于 `TreeWalker` 深度遍历文本节点，不破坏网页原有样式。
* **正则去噪**：内置黑名单（如 HTML, POST 等）和正则加权，大幅降低 8 位随机 ID 误判。
* **事件劫持**：在 BBS 标题中点击时，优先拦截跳转请求以弹出预览窗。

---

## 📄 开源协议 | License

本项目遵循 [MIT License](LICENSE) 协议开源。

---

## ⚠️ 免责声明 | Disclaimer

本插件仅作为网页内容辅助识别工具，不存储、不分发、不提供任何视频资源。请在遵守当地法律法规的前提下使用。
This extension is only a helper tool for content identification and does not store or distribute any media resources.
