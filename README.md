# Local Text Comparison Tool

> A simple, privacy-first text comparison tool that runs entirely in your browser.
>
> 这是一个简单、注重隐私的文本对比工具，完全在浏览器中运行。

## 📖 Background / 项目背景

This tool was inspired by the need to compare different versions of AI prompts. When optimizing prompts, we often create multiple versions with small tweaks, and it becomes difficult to track what exactly was changed later on. This lightweight tool solves that problem with clear visual diffs, without any privacy concerns.

这个工具的灵感来源于对比不同版本AI提示词的需求。在优化提示词时，我们经常会创建多个带有细微调整的版本，之后很难追踪到底修改了什么内容。这个轻量级工具通过清晰的可视化差异展示解决了这个问题，完全没有隐私泄露风险。

## ✨ Features / 功能特性

### Core Features / 核心功能
- 🔒 **100% Local Processing** - All operations run entirely in your browser, no data is ever uploaded to any server
- 📝 **Multi-format Support** - Compare plain text, TXT files, Word documents (.docx), PDF files, and Markdown files
- 🎯 **Three Comparison Modes**
  - Character-level comparison (precision to each character)
  - Word-level comparison (granularity by words)
  - Line-level comparison (ideal for long texts and code)
- 🎨 **Clear Visualization**
  - 🟢 Green highlight for added content
  - 🔴 Red highlight + strikethrough for deleted content
  - 🟠 Orange highlight for modified content
- 📊 **Real-time Statistics** - Shows count of additions, deletions, and modifications
- ⚡ **Fast Performance** - Optimized algorithm handles very long texts efficiently

### 核心功能
- 🔒 **100%本地处理** - 所有操作完全在浏览器中运行，没有任何数据会上传到服务器
- 📝 **多格式支持** - 支持对比纯文本、TXT文件、Word文档(.docx)、PDF文件和Markdown文件
- 🎯 **三种对比模式**
  - 字符级对比（精确到每个字符）
  - 词语级对比（按词语粒度）
  - 行级对比（适合长文本和代码）
- 🎨 **清晰可视化**
  - 🟢 绿色高亮显示新增内容
  - 🔴 红色高亮+删除线显示删除内容
  - 🟠 橙色高亮显示修改内容
- 📊 **实时统计** - 显示新增、删除、修改的数量
- ⚡ **高性能** - 优化算法可高效处理超长文本

## 🚀 Usage / 使用方法

### Option 1: Quick Start / 方式一：快速启动
1. Double-click `启动工具.bat` (Windows only)
2. The tool will open automatically in your default browser

### 方式一：快速启动
1. 双击 `启动工具.bat` （仅Windows系统）
2. 工具会自动在默认浏览器中打开

### Option 2: Manual Start / 方式二：手动启动
1. Simply open `index.html` in any modern web browser
2. No installation or server required

### 方式二：手动启动
1. 直接在任意现代浏览器中打开 `index.html`
2. 无需安装，无需服务器

### How to Compare / 对比操作
1. Paste text directly into the left (original) and right (modified) input boxes
2. Or click "Upload File" to select documents to compare
3. Click "Start Comparison" button or press `Ctrl + Enter`
4. View the highlighted differences in the result section

### 对比操作
1. 直接将文本粘贴到左侧（原始）和右侧（修改后）输入框
2. 或点击"上传文件"选择要对比的文档
3. 点击"开始对比"按钮或按 `Ctrl + Enter`
4. 在结果区域查看高亮显示的差异

## 📋 Requirements / 环境要求

- Any modern web browser (Chrome 90+, Firefox 88+, Edge 90+, Safari 14+)
- No server, no dependencies, no Node.js required
- Works on Windows, Mac, Linux, and even mobile devices

## 环境要求

- 任意现代网页浏览器（Chrome 90+, Firefox 88+, Edge 90+, Safari 14+）
- 无需服务器，无需依赖，无需Node.js
- 支持Windows、Mac、Linux，甚至移动设备

## 🧪 Portability / 可移植性

This tool is 100% self-contained in a single HTML file. Anyone who clones the repository can use it immediately without any additional setup. There are no dependencies on local paths or system configurations.

本工具完全自包含在单个HTML文件中，任何人克隆仓库后都可以立即使用，无需任何额外设置。不依赖任何本地路径或系统配置。

## 📁 Project Structure / 项目结构

```
TextComparison/
├── index.html              # Main application file / 主应用文件
├── 启动工具.bat             # Windows quick start script / Windows快速启动脚本
├── README.md               # This documentation / 项目文档
├── UPDATE_PLAN.md          # Update plan (not tracked by git) / 更新计划（git不跟踪）
└── TestDatas/              # Test documents (not tracked by git) / 测试文档（git不跟踪）
    ├── test.txt
    ├── test.md
    ├── test.docx
    ├── test.doc
    └── test.pdf
```

## 🛡️ Privacy Guarantee / 隐私保障

✅ All processing happens locally in your browser  
✅ No network requests of any kind  
✅ No data is stored or transmitted anywhere  
✅ Open source code can be fully audited

✅ 所有处理都在你的浏览器本地完成  
✅ 没有任何网络请求  
✅ 没有数据被存储或传输到任何地方  
✅ 开源代码可完全审计

## 📝 Note / 说明

This is a small, simple tool built to solve a specific practical problem. It focuses on core functionality without unnecessary bloat.

这只是一个用来解决特定实际问题的简单小工具，专注于核心功能，没有不必要的臃肿特性。

## 📄 License / 许可证

MIT License - Feel free to use and modify as needed.
