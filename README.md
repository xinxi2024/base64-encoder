# Sloaner Base64转换器

![Sloaner Logo](https://img.shields.io/badge/Sloaner-Base64转换器-3a86ff?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGF0aCBkPSJNOCAxMGwxMi0xMCIvPjxwYXRoIGQ9Ik0yMCA0djE2Ii8+PHBhdGggZD0iTTQgNGExIDEgMCAwIDAgLTEgMXYxMGExIDEgMCAwIDAgMSAxaDE2Ii8+PC9zdmc+)

## 项目简介

Sloaner Base64转换器是一个简单高效的Web工具，用于在文本与Base64编码之间进行转换，并支持图片到Base64的编码与解码。该工具完全在浏览器中运行，无需服务器支持，保证了数据的安全性和隐私性。

### 功能特点

- **文本转换**: 
  - 支持文本到Base64的编码
  - 支持Base64到文本的解码
  - 完整支持UTF-8字符集，包括中文、特殊字符等

- **图片转换**:
  - 支持将图片转换为Base64编码
  - 支持将Base64编码转换回图片预览
  - 自动检测图片MIME类型

- **用户体验**:
  - 简洁现代的UI设计
  - 响应式布局，适配各种设备
  - 便捷的复制功能
  - 拖放上传图片支持

## 使用方法

### 在线使用

1. 直接访问[Sloaner Base64转换器](https://sloaner.com/tools/base64)
2. 选择相应的转换选项卡（文本转换或图片转换）
3. 输入需要转换的内容或上传图片
4. 点击相应的转换按钮
5. 复制转换结果或查看解码的图片

### 本地部署

1. 克隆或下载本仓库
2. 直接在浏览器中打开`index.html`文件
```bash
# 例如使用Visual Studio Code的Live Server插件
code index.html
# 或直接双击打开HTML文件
```

3. 无需安装任何依赖，即可使用全部功能

## 技术实现

- **纯前端实现**: 使用HTML, CSS和原生JavaScript开发
- **响应式设计**: 基于Flexbox和媒体查询实现的响应式布局
- **现代化UI**: 使用CSS变量、过渡和阴影等效果
- **文件API**: 利用FileReader API实现图片处理
- **Unicode支持**: 使用TextEncoder和TextDecoder确保跨语言字符集支持

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- Opera 47+

## 贡献指南

欢迎通过以下方式参与项目贡献：

1. 提交Bug和功能需求
2. 审查代码
3. 提交Pull Request

## 许可证

本项目采用[MIT许可证](LICENSE)。

## 关于作者

Sloaner Base64转换器是Sloaner工具集的一部分，致力于提供简单高效的在线工具。 